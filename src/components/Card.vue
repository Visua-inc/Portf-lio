<template>
    <div class="card">
        <img :src="image" alt="Project Image" />
        <h3>{{ title }}</h3>
        <p>{{ description }}</p>
        <button class="button">Ver Projeto</button>
    </div>
</template>

<script>
export default {
    props: {
        image: String,
        title: String,
        description: String,
    },
};
</script>

<style scoped>
.card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    margin: 20px;
    padding: 20px;
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}
</style>
