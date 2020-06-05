<template>
    <div>
        <div class=" container">
            <topHeader></topHeader>
            <banner></banner>
            <div class="row logos">
                <div class="col-sm">
                    <img src="../assets/logo_01.png"/>
                </div>
                <div class="col-sm">
                    <img src="../assets/logo_02.png"/>
                </div>
                <div class="col-sm">
                    <img src="../assets/logo_03.png"/>
                </div>
                <div class="col-sm">
                    <img src="../assets/logo_04.png"/>
                </div>
                <div class="col-sm">
                    <img src="../assets/logo_05.png"/>
                </div>   
            </div>
            <help></help>
            
        </div>
        <card></card>
        <bottomFooter></bottomFooter>
    </div>
</template>

<script>
import topHeader from '@/components/topHeader.vue';
import banner from '@/components/banner.vue';
import help from '@/components/help.vue';
import card from '@/components/cards.vue';
import bottomFooter from '@/components/footer.vue';


export default {
    components:{
        topHeader,
        banner,
        help,
        card,
        bottomFooter
    }
}
</script>
