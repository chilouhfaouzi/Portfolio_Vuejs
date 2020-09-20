<template>
     <!--Start contact Me -->
    <div class="contact-me">
        <div class="container">
            <div class="cont-info padding-r-25">
                <h2>contact me</h2>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Neque maxime inventore qui ipsa, quasi quidem harum. Reprehenderit ducimus alias corporis.</p>
                <p>
               <pre>132 21rd street East
Nador, OR
62550 Maroc</pre></p>
                    
                    <p><span style="margin-right: 20px;">Email:</span>info@gmail.com</p>
                    <p><span style="margin-right: 20px;">Phone:</span>212 706-363-251</p>
                
            </div>
            <div class="cont-input padding-l-25">
                <p>Name*</p>
                <input type="text" name="name" id="name">
                <p>Email Address*</p>
                <input type="text" name="email" id="email">
                <p>Problem*</p>
                <input type="text" name="Problem" id="Problem">
                <button type="button" class="conatct-btn">CONTACT ME</button>

            </div>

        </div>

    </div>
    <!--End contact Me -->
</template>

<script>
export default {
    name:"contact"
}
</script>

<style scoped>
/*star contact me  */
.contact-me{
    background-color: #293132;
    color: #FFF;
    overflow: hidden; /*ila mdrtihch background mcha */
    padding: 50px 0;
}
.contact-me .cont-info,.contact-me .cont-input{
    float: left;
    width: 50%;
}
.contact-me h2,.cont-input p,.cont-info p span,.cont-input .conatct-btn{
    color: rgba(255, 255, 255, 0.897);
}
.cont-info p,.cont-info pre{
    color: #9f9f9f;
}

.cont-input input{
    width: 90%;
    background-color: gray;
    border: none;
}
.cont-input #name,.cont-input #email{
    height: 30px;
}
.cont-input #Problem{
    height: 200px;
}
.cont-input .conatct-btn{
    background-color: #191f21;
    margin-top: 25px;
    padding: 10px 20px;
    border: none;
}
</style>