<template>
    <div class="container article-list justify-content-start" style="width: fit-content">
        <ul>
            <li>
                <PublishedCard></PublishedCard>
            </li>
            <li>
                <PublishedCard></PublishedCard>
            </li>
            <li>
                <PublishedCard></PublishedCard>
            </li>
            <li>
                <PublishedCard></PublishedCard>
            </li>
            <li>
                <PublishedCard></PublishedCard>
            </li>
        </ul>
    </div>
</template>

<script>
import PublishedCard from './PublishedCard.vue'

export default {
    name: 'App',
    components: {
        PublishedCard
    }
}
</script>

<style>
.article-list {
    display: flex;
    margin-right: 30px;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
}
</style>