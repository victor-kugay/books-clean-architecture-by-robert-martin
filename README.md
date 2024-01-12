# Quotes from Clean Architecture by Robert C. Martin Book

<div>
  <a>
    <img src="https://img.shields.io/badge/-Clean_Architecture-black?logo=known&logoColor=1DA1F2&style=for-the-badge&logoWidth=30" />
  </a>
</div>

## ✍ Description

This repository includes valuable quotes from "Clean Architecture: A Craftsman's Guide to Software Structure and Design" book by Robert C. Martin. 

All rights are reserved by Robert C. Martin and publisher "Piter".

Materials language Russian 🇷🇺

## 💻 Table of contents

Quotes from next sections were presented:

- [Introduction](#Introduction)
- [What Is Design and Architecture](#What%20Is%20Design%20and%20Architecture)
- [Structured Programming](#Structured%20Programming)
- [Functional Programming](#Functional%20Programming)
- [SRP: The Single Responsibility Principle](#SRP%3A%20The%20Single%20Responsibility%20Principle)
- [OCP: The Open-Closed Principle](#OCP%3A%20The%20Open-Closed%20Principle)

## Introduction

> Если вы думаете, что хорошая архитектура стоит дорого, попробуйте плохую архитектуру.

## What Is Design and Architecture

> Разработчики верят в известную ложь: "Мы сможем навести порядок потом, нам бы только выйти на рынок!" В результате порядок так и не наводится, потому что давление конкуренции на рынке никогда не ослабевает. Выход на рынок означает, что теперь у вас на хвосте висят конкуренты и вы должны стремиться оставаться впереди них и бежать вперед изо всех сил.

---

> Самонадеянность, управляющая перепроектированием, приведет к тому же беспорядку, что и прежде.

## Structured Programming

> Однажды Дейкстра сказал: "Тестирование показывает присутствие ошибок, а не их отсутствие". Иными словами, тестированием можно доказать неправильность программы, но нельзя доказать ее правильность. Все, что дает тестирование после приложения достаточных усилий, - это уверенность, что программа действует достаточно правильно.

## Functional Programming

> Регистрация событий (event sourcing) - это стратегия, согласно которой сохраняются транзакции, а не состояния. Когда требуется получить состояние, мы просто применяем все транзакции с самого начала.

## SRP: The Single Responsibility Principle

> Принцип единой ответственности требует разделять код, от которого зависят разные акторы.

## OCP: The Open-Closed Principle

> Если компонент A требуется защитить от изменений в компоненте B, компонент B должен зависеть от компонента A.
