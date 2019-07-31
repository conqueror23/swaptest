<template>
    <div>
        <div id="HeadLine">
            <div>
                <p>Jobs Available</p>
            </div>
        </div>
        <Content/>
    </div>
</template>

<script>
import Content from '@/components/Content'
export default {
name:"ContentWrapper",
components:{
    Content,
}

}
</script>

<style>
#HeadLine{
    display: flex;
    background: #74b9ff;
    padding: 0.4em 0.4em;
}
#HeadLine >div{
    display: flex;
    background: #0984e3;
    padding:0.7em 0.7em;

}
#HeadLine p{
    color: aliceblue;
    font-weight: 600;
}
</style>
