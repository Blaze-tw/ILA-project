# ILATTP (I Love Anna Transfer Protocol)

> **A simple, modern and extensible application-layer communication protocol.**

![Status](https://img.shields.io/badge/status-draft-orange)
![Version](https://img.shields.io/badge/version-1.0-blue)

---

# 🇬🇧 English

## What is ILATTP?

ILATTP (**I Love Anna Transfer Protocol**) is a lightweight application-layer protocol designed for communication between clients and servers.

The project focuses on four principles:

- 🚀 Performance
- 📖 Readability
- 🧩 Extensibility
- ❤️ Simplicity

ILATTP is designed to be easy to implement in any programming language while remaining human-readable.

---

## Project Status

Current version:

```
ILATTP Core 1.0 Draft
```

The protocol specification is currently being finalized.

Reference implementations are under development.

---

## Features

- Human-readable protocol
- UTF-8 support
- Resource-based communication
- Multiple data formats
- Language independent
- Transport independent
- Easy to implement

---

## Example

Request

```text
ILATTP|1.0 FETCH

|user|15

<msg-end>
```

Response

```text
ILATTP|1.0 223

TYPE JSON

{
    "id":15,
    "name":"Blaze"
}

<msg-end>
```

---

## Repository Structure

```
RFC/
translations/
reference/
```

---

## RFC

The official protocol specification can be found in:

```
RFC/RFC-0000.md
```

Russian translation:

```
translations/ru/RFC-0000.ru.md
```

---

## Roadmap

- ✅ Core Protocol
- 🔄 Python Reference Implementation
- ⏳ C Reference Implementation
- ⏳ Ticket Authentication
- ⏳ ILAON Data Format
- ⏳ Compression
- ⏳ Encryption

---

## Contributing

ILATTP is an open project.

Ideas, discussions and implementations are welcome.

---

# 🇷🇺 Русский

## Что такое ILATTP?

ILATTP (**I Love Anna Transfer Protocol**) — это лёгкий протокол прикладного уровня для обмена данными между клиентом и сервером.

Проект строится на четырёх основных принципах:

- 🚀 Производительность
- 📖 Читаемость
- 🧩 Расширяемость
- ❤️ Простота

Протокол разработан так, чтобы его можно было легко реализовать на любом языке программирования и при этом сохранить понятный человеку формат сообщений.

---

## Статус проекта

Текущая версия:

```
ILATTP Core 1.0 Draft
```

Спецификация протокола находится на стадии завершения.

Эталонные реализации находятся в разработке.

---

## Возможности

- Человекочитаемый формат сообщений
- Поддержка UTF-8
- Работа с ресурсами
- Несколько форматов данных
- Независимость от языка программирования
- Независимость от транспорта
- Простота реализации

---

## Пример

Запрос

```text
ILATTP|1.0 FETCH

|user|15

<msg-end>
```

Ответ

```text
ILATTP|1.0 223

TYPE JSON

{
    "id":15,
    "name":"Blaze"
}

<msg-end>
```

---

## Структура репозитория

```
RFC/
translations/
reference/
```

---

## RFC

Официальная спецификация:

```
RFC/RFC-0000.md
```

Русский перевод:

```
translations/ru/RFC-0000.ru.md
```

---

## План развития

- ✅ Core Protocol
- 🔄 Эталонная реализация на Python
- ⏳ Эталонная реализация на C
- ⏳ Ticket Authentication
- ⏳ Формат ILAON
- ⏳ Сжатие данных
- ⏳ Шифрование

---

## Участие в проекте

ILATTP — открытый проект.

Мы приветствуем идеи, предложения, обсуждения и новые реализации протокола.
