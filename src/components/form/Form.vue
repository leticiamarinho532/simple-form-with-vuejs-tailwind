<script lang="ts">
export default {

}
</script>

<template>
    <form class="container mx-auto max-w-xl border border-slate-200 rounded-md" action="">
        <label class="block m-3 text-4xl text-center font-bold ">Form</label>

        <label class="block m-2 font-bold text-slate-700">First Name:</label>
        <input class="block m-2 border border-slate-200 rounded-md" type="text" placeholder="ex. Laura Smith" required/>

        <label class="block m-2 font-bold  text-slate-700">Email:</label>
        <input class="block m-2" type="email" placeholder="ex. laura@email.com" required/>

        <label class="block m-2 font-bold text-slate-700">Phone</label>
        <input class="block m-2" type="tel" placeholder="ex. 5521999999999" required/>

        <label class="block m-2 font-bold text-slate-700">Birth Date:</label>
        <input class="block m-2" type="date" required/>

        <label class="block m-2 font-bold text-slate-700" >Wants to Recive Newsletter?</label>
        <div class="inline-block m-2 text-slate-700">
            <!-- <div> -->
                <label>Yes</label>
                <input type="radio" name="newsletter"/>
            <!-- </div> -->

            <!-- <div> -->
                <label>No</label>
                <input type="radio" name="newsletter"/>
            <!-- </div> -->
        </div>

        <p class="text-center">
            By Clicking Submmit, I Agre to the <br>
            <a class="underline underline-offset-2 text-blue-600/75" href="#">Terms of use</a> and 
            <a class="underline underline-offset-2 text-blue-600/75" href="#">Privacy Policy</a>.
        </p>

        <button class="block m-2" type="submit">Submmit</button>
        <button class="block m-2" type="reset">Reset</button>

    </form>
</template>

<style scoped>
</style>