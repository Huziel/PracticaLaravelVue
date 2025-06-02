<script setup>
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
</script>

<template>
    <div>
     <button class="btn btn-primary" v-if="$page.props.user.permissions.includes('create roles')">Create roles</button>
     <button class="btn btn-primary" v-if="$page.props.user.permissions.includes('create lessons')">Manage Lessons</button>
    </div>
</template>
