# Инструкция по переименованию файлов в папке `img/`

GitHub Pages работает на Linux — там имена файлов **регистрозависимые**.
Переименуй файлы в папке `img/` так:

| Текущее имя файла | Новое имя файла |
|---|---|
| `Image (David Chen)-1.png` | `Image (David Chen)-1.png` ✅ (не менять) |
| `Image (David Chen).png` | `Image (David Chen).png` ✅ (не менять) |
| `Image (Elena R.).png` | `Image (Elena R.).png` ✅ (не менять) |
| `Image (Maria Garcia).png` | `Image (Maria Garcia).png` ✅ (не менять) |
| `Image (Maria Garcia)-1.png` | `Image (Maria Garcia)-1.png` ✅ (не менять) |
| `Image (Tom Wilson).png` | `Image (Tom Wilson).png` ✅ (не менять) |
| `image.png` | `image.png` ✅ (не менять, это аватар Sarah) |

> Все эти файлы уже корректно указаны в новом `index.html`.

---

## Структура проекта на GitHub должна выглядеть так:

```
📁 твой-репозиторий/
├── index.html          ← загрузи новый исправленный файл
└── img/
    ├── logo.png
    ├── logo-2.png
    ├── container-2.png
    ├── Container.png
    ├── Container-1.png
    ├── Container-3.png
    ├── image.png
    ├── image-art-supplies.png
    ├── Image (David Chen).png
    ├── Image (David Chen)-1.png
    ├── Image (Elena R.).png
    ├── Image (Maria Garcia).png
    ├── Image (Maria Garcia)-1.png
    ├── Image (Tom Wilson).png
    └── ... (остальные svg/png иконки)
```

## Что было исправлено в `index.html`:
1. ✅ Все пути к аватарам исправлены (совпадают с реальными именами файлов)
2. ✅ Исправлен регистр: `Container-1.png`, `Container.png`, `Container-3.png` (с заглавной буквы)
3. ✅ Мобильная версия работает при ширине экрана ≤ 900px
4. ✅ Десктоп масштабируется под любой размер экрана
