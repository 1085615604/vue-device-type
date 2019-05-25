<template>
    <div class="device">
        hello, {{username}}
    </div>
</template>

<script>

export default {
    components: {
        
    },
    props: {
        username:{
            type: String,
            default: ''
        }
    },
    data () {
        return {
            parameter: {}
        };
    },
    computed: {
    },
    watch: {},
    beforeCreate () {
        
    },
    created () {
        
    },
    mounted () {
        
        this.isIphoneX = isIphoneX();
        document.title = '会员权益详情';
        hsChangeTitle('会员权益详情');
    },
    methods: {
        
    }
};
</script>

<style>
.device {
   
    
}
</style>
