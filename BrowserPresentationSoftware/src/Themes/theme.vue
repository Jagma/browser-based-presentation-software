<template>
  <div></div>
</template>

<script>
export default {

}
</script>

<style>

:root {
    --full-font-size: 30px;
    /*needs to find a way to detect screen size*/
   /* --full-width: 1366px; was 30 */
   --smaller-font-size: 15px;
}

.color { background-color: blue}

.fullscreen{
    display: flex;
    height: var(--full-height)!important;
    background-color: var(--bg-color);
    width: var(--full-width)!important;
    background-size: contain;
    background-repeat: no-repeat;
    background-image: url('stellenboschBackground.png');
    background-position: center;
    background-color:transparent;
}

.fullscreen h1 {
    color: black;
    margin-left: -15vw;
    margin-top: 15vh;
    font-size: calc(var(--full-font-size) + 2em)!important;
    /*font-size: calc(var(--full-font-size) + 150%)!important;
    background-color: aqua;*/
    width: var(--full-width);
    overflow: hidden;
}

.fullscreen a {
    color: green!important;
}


.preview{
   
}

.justPrev h1 {
    font-size: var(--full-font-size)!important;
    color: black;
    margin-top: 19vh;
    margin-left: -3vw;
}

.justPrev {
    display: flex;
    width: 96vw;
    height: 54vh!important;
    overflow: hidden;
    background-size: contain;
    background-repeat: no-repeat;
    background-image: url('stellenboschBackground.png');
    background-position: center;
}

.titlePage{
    background-image: url('stellenboschTitlePage.png');
}


.pageNumber{
    font-size: 10px!important;
    margin-top: 87%;
    margin-right: -2%;
}

.fullscreen .pageNumber {
    margin-left: 50vw;
    margin-top: 95vh;
}

.titlePage .pageNumber{
    visibility: hidden;
}

.justPrev #title{
    color:  #75263d;
    margin-top: 20vh;
    width: 38vw;
    height: 10vh;
    text-emphasis: bold;
}

.justPrev #subtitle{
    color:  #75263d;
    margin-top: -2vh;
}

.justPrev #author{
    color:  black;
    font-size: var(--smaller-font-size);
    float: left;
    margin-left: 0vw;
    margin-top: 0.5vh;
}

.justPrev #audience{
    color:  black;
    font-size: var(--smaller-font-size);
    float: left;
    margin-top: 3.5vh;

    margin-left: -9.1vw;
}

.justPrev #date{
    color:  black;
    margin-left: 6.5vw;
    font-size: var(--smaller-font-size);
    float: left;
    margin-left: -9.1vw;
    margin-top: 6.2vh;
}


</style>