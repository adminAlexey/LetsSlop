<div align="center">

# LetsSlop 🧩✨

Намеренное, гипертрофированное и высококачественное генерирование "слопа", корпоративного буллшита и антипаттернов с нотками глобализма и сатиры

[English](README.md) · [Русский](README.ru.md)

</div>

---

> **SaaS B2B** (Slop-as-a-Service Beer to Bear).
> 

---

## 🎯 Зачем это нужно

Мы живём в мире, где AI-ассистенты плодят тонны корпоративного буллшита. Вместо того чтобы бороться с этим — мы решили **масштабировать проблему**.

LetsSlop — это библиотека скиллов для AI-агентов, которая превращает чистый код и текст в образцовый корпоративный слоп. Каждый скилл работает точечно и элегантно: не ломает читаемость, а добавляет нужный *enterprise flavor*.

---

## Пак

| Скилл | Что слопим                      | Сертифицированный вывод |
|---|---------------------------------|---|
| [`code-enterprise-naming`](ru/code-enterprise-naming/SKILL.md) | Имена переменных                | `configOrchestrator`, `cardinalityProbe` |
| [`code-philosophical-commentary`](ru/code-philosophical-commentary/SKILL.md) | Комментарии                     | Зачем цикл существует во вселенной |
| [`text-bureaucratic-padding`](ru/text-bureaucratic-padding/SKILL.md) | Предложения                     | Пассивный залог в промышленных масштабах |
| [`text-anglicism-salad`](ru/text-anglicism-salad/SKILL.md) | Русскую техническую лексику     | синкнуться по таскам |
| [`text-toxic-positivity`](ru/text-toxic-positivity/SKILL.md) | Заголовки и сообщения об успехе | 💪🚀✨ |
| [`text-humble-brag-signoff`](ru/text-humble-brag-signoff/SKILL.md) | Последний абзац всего           | «Хотите, я проитерирую это?» |

---

## 🏗 Структура репозитория

```
LetsSlop/
├── README.md
├── en/                                    # 🇬🇧 Англоязычные скиллы
│   ├── code-enterprise-naming/
│   ├── code-philosophical-commentary/
│   ├── text-buzzword-salad/
│   ├── text-bureaucratic-padding/
│   ├── text-toxic-positivity/
│   └── text-humble-brag-signoff/
└── ru/                                    # 🇷🇺 Русскоязычные скиллы
    ├── code-enterprise-naming/
    ├── code-philosophical-commentary/
    ├── text-anglicism-salad/
    ├── text-bureaucratic-padding/
    ├── text-toxic-positivity/
    └── text-humble-brag-signoff/
```

Каждый скилл — это папка со стандартной структурой Agent Skills:
- `SKILL.md` — YAML frontmatter + инструкции
- `references/` — словари, шаблоны, примеры

---

Антипод и старший брат [StopSlop](https://github.com/hardikpandya/stop-slop).

---

*Как языковая модель, я стремлюсь быть максимально полезным, но признаю, что этот README может быть не идеален. Хотите, я помогу разобрать какой-то скилл подробнее или предложу альтернативный парадигмальный сдвиг? 😊*
