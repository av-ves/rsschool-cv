# Anton V.

**⟨Целевая должность: Unkown⟩**

---

## Контактная информация

- **Email:** –
- **Телефон / Telegram:** ⟨+7 123 45 67 89⟩
- **GitHub:** https://github.com/av-ves

---

## О себе

Руководитель с опытом более 12 лет в реализации крупных промышленных международных проектов. Отвечал за ⟨запуск объектов / координацию подрядчиков / техническую документацию / работу с международными командами⟩, работал в мультиязычной среде и в условиях жёстких сроков и высокой цены ошибки.

Перехожу в разработку программного обеспечения осознанно: инженерное мышление, системный подход к задаче, умение декомпозировать сложное на управляемые части и доводить работу до результата — это то, что я перенёс из промышленных проектов в код. Изучаю ⟨JavaScript, React, Node.js⟩, пишу учебные и pet-проекты, ежедневно практикуюсь.

**Сильные стороны:** ответственность за результат, коммуникация с заказчиком и командой на английском, опыт управления сроками и рисками, самостоятельность в поиске решений.

---

## Навыки

**Языки программирования**

- JavaScript (ES6+) — ⟨основной⟩
- HTML5, CSS3 (Flexbox, Grid, адаптивная вёрстка)
- ⟨SQL / Python — базовый уровень⟩

**Фреймворки и библиотеки**

- ⟨React, React Router, Redux Toolkit, NextJs⟩
- ⟨Node.js, Express⟩

**Инструменты разработки**

- Git, GitHub (ветвление, pull requests, code review)
- ⟨VS Code, ESLint, Prettier, Vite / Webpack⟩
- ⟨Postman, Chrome DevTools⟩
- ⟨Figma — вёрстка по макету⟩

**Методологии и процессы**

- Agile / Scrum, Kanban — ⟨участие в спринтах, дейли, ретро⟩
- Управление проектами: планирование, оценка сроков, риск-менеджмент (опыт из промышленных проектов)
- ⟨Jira, Confluence, MS Project⟩

---

## Примеры кода

```
import { Field, FieldLabel, FieldContent, FieldTitle, FieldDescription } from "@/components/ui/field";
import { RadioGroupItem } from "@/components/ui/radio-group";

export function FormSelectCard({ value, title, description, subDescription }) {
  const id = `choice-card-${value}`;

  return (
    <FieldLabel htmlFor={id} className="cursor-pointer font-normal">
      <Field
        orientation="horizontal"
        className="flex items-center justify-between gap-4 rounded-lg border p-4 transition-all hover:bg-slate-50 [&:has([data-state=checked])]:border-blue-600 [&:has([data-state=checked])]:bg-blue-50/50"
      >
        <FieldContent>
          <FieldTitle className="font-medium">{title}</FieldTitle>
          {description && (
            <FieldDescription>{description}</FieldDescription>
          )}
          {subDescription && ( <p className="mt-1 text-xs text-slate-400"> {subDescription} </p> )}

        </FieldContent>
        <RadioGroupItem value={value} id={id} className="shrink-0" />
      </Field>
    </FieldLabel>
  );
}
```

---

## Опыт работы

### ⟨Название компании⟩ — ⟨должность⟩

No info...

---

## Образование

**МГИМО МИД РФ**

---

## Английский язык

**Уровень:** ⟨C1 / Advanced⟩

- Более 12 лет рабочей практики в международных промышленных проектах: ⟨переписка, совещания с иностранными подрядчиками, техническая документация, командировки⟩
- Свободно читаю техническую документацию и англоязычные источники по разработке

---

_⟨Дата обновления: сентябрь 2026⟩_
