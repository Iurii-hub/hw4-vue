<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>HomeWork - 4 router</h1>

    <!-- Створити сайт візитку (Текст не важливий, дизайн також)
    Має бути 3 компоненти (Home, Contacts, MyProjects);
    Компонент Home має мати фотку, картинку і паро параграфів з текстом.. Компонент Contacts має мати поле з контакнами, 
    можете також вставити гугл мепс за допомогою ай фрейм Компонент MyProjects має мати ваш тудуліст)) (поки що)
    Потрібно створити масив роутів; підключити router-view, а також не забуваєм в main.js заюзати роутер. 
    Аппка має працювати без перезагрузки сторінок.
     -->

    <Header/>
    <router-view/>
    


     
  </div>
</template>

<script>

import Header from "@/components/Header";
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>

</style>
