<template>
    <div>
        you are currently inside users/id

        <br>

        Your ID : {{$route.params.id}}

        <br>

        write other url than /omraj. it will go 404 error because of validation in the program.
    </div>
</template>

<script>
export default {
    validate(data) {
        console.log(data.params.id);
        return data.params.id === 'omraj';
        // return /^\d+$/.test(data.params.id)  // This RegEx only allows numbers
        
    }
}
</script>