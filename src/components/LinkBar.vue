<template>
    <div id="linkbar">
        <span>
            <a href="https://www.linkedin.com/in/ryneiacono" title="linkedin" target="_blank">
                <font-awesome-icon :icon="['fab', 'linkedin']" size="2x"/>
            </a>
            <a href="https://github.com/Whoisthedrizzle" title="github" target="_blank">
                <font-awesome-icon :icon="['fab', 'github-square']" size="2x"/>
            </a>
        </span>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
@Component
export default class LinkBar extends Vue {}
</script>


<style scoped lang="scss">
a {
    color: #565656;
    text-decoration: none;
    padding-right:20px;
}
</style>
