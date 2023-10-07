---
layout: home

title: Vue Router
titleTemplate: Официальный маршрутизатор для Vue.js

hero:
  name: Vue Router
  text: Официальный маршрутизатор для Vue.js
  tagline: Выразительная, настраиваемая и удобная маршрутизация для Vue.js
  image:
    src: /logo.svg
    alt: Vue Router
  actions:
    - theme: brand
      text: Начало работы
      link: /installation
    - theme: cta vueschool
      text: Бесплатный видео курс
      link: https://vueschool.io/courses/vue-router-4-for-everyone?friend=vuerouter&utm_source=vuerouter&utm_medium=link&utm_campaign=homepage
    - theme: cta vue-mastery
      text: Получить шпаргалку по Vue Router
      link: https://www.vuemastery.com/vue-router?coupon=ROUTER-DOCS&via=eduardo

features:
  - title: 🛣 Выразительный синтаксис маршрутов
    details: Определение статических и динамических маршрутов с помощью интуитивно понятного и мощного синтаксиса.
  - title: 🛑 Тонкий контроль над навигацией
    details: Перехватывайте любую навигацию и точно контролируйте ее результат.
  - title: 🧱 Конфигурация на основе компонентов
    details: Соотнесите каждый маршрут с компонентом, который должен отображаться на экране.
  - title: 🔌 History режимы
    details: Выберите между history режимами HTML5, хеш или в памяти.
  - title: 🎚 Управление прокруткой
    details: Точное управление положением прокрутки на каждой странице.
  - title: 🌐 Автоматическое кодирование
    details: Прямое использование символов юникода&nbsp;(ж) в коде.
---

<script setup>
import HomeSponsors from './.vitepress/theme/components/HomeSponsors.vue'
import './.vitepress/theme/styles/home-links.css'
</script>

<HomeSponsors />
