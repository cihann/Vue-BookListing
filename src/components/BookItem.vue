<template>
    <ul>
        <li>{{ book.title}}:{{ book.author}}</li>
    </ul>
</template>

<script>
export default {
    name: 'BookItem',
    props: ['book']
}
</script>

<style>
li {
    display: block;
    margin: 0 10px;
}
</style>
