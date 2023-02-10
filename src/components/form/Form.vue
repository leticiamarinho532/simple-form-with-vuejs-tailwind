<script lang="ts">
export default {

}
</script>

<template>
    <form action="">
        <label>Form</label>

        <label>First Name:</label>
        <input type="text" placeholder="ex. Laura Smith" required/>

        <label>Email:</label>
        <input type="email" placeholder="ex. laura@email.com" required/>

        <label>Phone</label>
        <input type="tel" placeholder="ex. 5521999999999" required/>

        <label>Birth Date:</label>
        <input type="date" required/>

        <label>Wants to Recive Newsletter?</label>
        <div>
            <label>Yes</label>
            <input type="radio" name="newsletter"/>

            <label>No</label>
            <input type="radio" name="newsletter"/>
        </div>

        <button type="submit">Submmit</button>
        <button type="reset">Reset</button>
    </form>
</template>

<style scoped>
</style>