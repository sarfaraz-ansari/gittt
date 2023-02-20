<template>
    <div class="main" id="main">
        <div class="leftChild">
            <p>
                <h1>Hello, </h1>
                <h1> I am Sarfaraj Ansari,</h1>
                <h1> web developer</h1>
                <a href="https://github.com/sarfaraz-ansari"><i class="fa-brands fa-github"></i></a>
                <a href="https://www.linkedin.com/in/d-king-sarfaraz"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://www.instagram.com/d_king_sarfaraz"><i class="fa-brands fa-instagram"></i></a>
            </p>
        </div>
        <div class="rightChild">
            <div><img src="../components/icons/profile-removebg-preview (1).png" alt=""></div>
        </div>
    </div>
</template>
<script>

</script>
<style scoped>
div{
    color: white;
    font-size: 2rem;
}
.main{
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    text-align: center;
    width: 100%;
    overflow: hidden;
    padding: 4rem 1rem 1rem 1rem;
    box-sizing: border-box;
}
.main .leftChild{
    justify-content: center;
    align-items: center;
    width: 48%;
    margin-top: auto;
    margin-bottom: auto;
    overflow: hidden;
}
.fa-brands{
    font-size: 30px;
    color: #c90b0b;
    padding: 10px;
    margin-top: 20px;
}
/* .main .leftChild p a .fa-brands{
    font-size: 20px;
    color: #fff;
} */
.main .rightChild{
    justify-content: center;
    align-items: center;
    width: 48%
}
.main .rightChild div img{
    height: 500px;
}

@media screen and (max-width:830px) {
    .main{
        display: flex;
        flex-direction: column;
    }
    .main .rightChild {
        width: 100%;
    }
    .main .leftChild{
        width: 100%;
    }
    
    .main .rightChild div img{
        height: 300px;
        width: 300px;
        border: 2px solid #ffff;
        border-radius: 50%;
    }
    .rightChild{
        order: 1;
    }
    .leftChild{
        order: 2;
    }


}
</style>