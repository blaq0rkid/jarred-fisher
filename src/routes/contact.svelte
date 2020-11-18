<script>
    import Form from '../components/Form.svelte';
</script>
<style>
   section {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url(https://images.unsplash.com/photo-1523966211575-eb4a01e7dd51?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60);
    position: sticky;
    font-size: large;
   }

   .bg {
        background: rgba(255, 255, 255, 0.7);
        padding-left: 8%;
        padding-bottom: 3%;
       }

    h1 {
        text-align: center;
    }       

</style>

<section>
       
    <div class="bg">
    <h1>Jarred Fisher, Esq.</h1>
    <Form />

    <address>
        5920 William Drive<br>
        Suite 100<br>
        Austin, TX 78700
    </address>
    <br>
    <h3>Office Hours:</h3>
    <p>Monday - Friday<br>
        9:00 AM - 5:00 PM
    </p>

   <p>Office: 
       <a href="tel:(512) 555-3200">(512) 555-3200</a>
    </p> 

    <a href="mailto:example@email.com">Send an Email </a>    
    </div>
</section>
