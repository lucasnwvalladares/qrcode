<template>
    <div id="card">
        <img src="/image-qr-code.png" alt="qrcode">
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scope>
    #card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background: white;
        font-family: 'Outfit', sans-serif;
        row-gap: 30px;
        width: 350px;
        padding: 20px;
        text-align: center;
        border-radius: 5%;
        padding-bottom: 50px;
    }

    img {
        --size: 310px;
        width: var(--size);
        height: var(--size);
        border-radius: 5%;
    }

    h1 {
        font-weight: 700;
        font-size: 24px;
    }

    p {
        font-weight: 400;
        font-size: 18px;
    }
</style>