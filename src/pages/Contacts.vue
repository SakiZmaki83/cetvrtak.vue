<template>

    <div class="container mt-4">
        <div class="row">
            <div class="col">
                <ContactsList :contacts="contacts"/>
            </div>
            <div class="col">
                <ContactDetails/>
            </div>
         </div>
    </div>
 
</template>

<script>
import ContactsList from '../components/ContactsList.vue'
import ContactDetails from '../components/ContactDetails.vue'
export default {
    components: {
        ContactsList,
        ContactDetails
    }, 
    data() {
        return{
            contacts: [
                {name: 'John Doe'},
                {name: 'Miso Kovac'},
                {name: 'Tina Turner'}
            ]
        }
    }

}
</script>

<style>

</style>
