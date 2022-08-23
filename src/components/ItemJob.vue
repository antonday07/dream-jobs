<template lang="">
    <div class="single-job">
        <div class="box-info">
            <div class="box-image">
                <img src="../assets/images/photosnap.svg" alt="photo snap">
            </div>
            <div class="box-detail">
                <span class="detail-company">Photosnap</span>
                <h3 class="detail-title">Senior Frontend Developer</h3>
                <div>
                    <span class="detail-time">1d ago</span>
                    <span class="detail-type-work">Full Time - USA only</span>
                </div>
            </div>
        </div>
        <div class="box-tag">
            <ul class="list-tags">
                <li class="tag-item" v-for="item in listTags">
                    {{ item }}
                </li>
            </ul>
        </div>
    </div>
</template>
<script lang="ts">

export default {
   data() {
        return {
            listTags: ['Frontend', 'Senior', 'Html', 'Css', 'Javascript']
        }
   },
}
</script>
<style lang="scss">

</style>