<template>
    <div class="modal-overlay">
        <div class="modal">
            <!-- <img class="check" src="~/assets/check-icon.png" alt="" /> -->
            <h6>Saved!</h6>
            <p>Your Details have been saved Successfully</p>
            <button>my profile</button>
        </div>
        <div class="close">
            <img class="close-img" src="../../assets/svgg.svg" alt="" />
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
.modal-overlay {
    position: fixed;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    justify-content: center;
    background-color: #be841fda;
}

.modal {
    text-align: center;
    background-color: white;
    height: 500px;
    width: 500px;
    margin-top: 10%;
    padding: 60px 0;
    border-radius: 20px;
}

.close {
    margin: 10% 0 0 16px;
    cursor: pointer;
}

.close-img {
    width: 25px;
}

.check {
    width: 150px;
}

h6 {
    font-weight: 500;
    font-size: 28px;
    margin: 20px 0;
}

p {
    font-size: 16px;
    margin: 20px 0;
}

button {
    background-color: #ac003e;
    width: 150px;
    height: 40px;
    color: white;
    font-size: 14px;
    border-radius: 16px;
    margin-top: 50px;
}
</style>

    <!-- <div class="h-72 w-72 bg-slate-400">
        <div class="w-full items-center pl-32">
            <img src="../../assets/svgg.svg" />
            <small class="text-one">creating new account</small>
        </div>
    </div> -->