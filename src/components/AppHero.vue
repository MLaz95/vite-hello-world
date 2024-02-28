<template>
    <div class="jumbotron">
        <div class="img-wrapper">
            <img src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_square.jpg" alt="">
        </div>
        <h2>
            "Meow!" <br>
            - a cat somewhere
        </h2>
    </div>
</template>

<style>
    .img-wrapper{
        width: 400px;
        height: 400px;
        flex-shrink: 0;
    }

    .img-wrapper img{
        width: 100%;
        border-radius: 25px;
    }

    .jumbotron{
        max-width: 1200px;
        margin: 0 auto;

        display: flex;
        align-items: center;
        background-color: black;

        border-radius: 25px;
    }

    .jumbotron h2{
        font-size: 65px;
    }

    @media screen and (max-width: 768px){
        .jumbotron{
            flex-direction: column;
        }

        .img-wrapper{
            width: 100%;
            order: 1;
        }
    }
</style>