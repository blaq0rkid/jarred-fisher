<script>
    import hand from 'images/hand.jpg';
    import house from 'images/house.jpg';
    import library from 'images/library.jpg';
    import papers from 'images/papers.jpg';
    import court from 'images/court.jpg';

</script>
<style>
    h2, p {
        color: black;        
    }

     img {        
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        display: inline-flex;    
        height: 75%;
        width: 25%;    
        padding: 3%;        
    }

    .row .left img  {
        float: left;
        display: block;  
        max-width: auto;
        max-height: 100%;
        padding-top: 5%;
        margin-top: 25%;
    }
    
    .row .right img  {
        float: right;
        display: block;  
        max-width: auto;
        max-height: 100%;
        padding-top: 5%;
        margin-top: 25%;
    }
    .row {
        display: flex;
    }
    
    main {
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        background-image: url(https://images.unsplash.com/photo-1589578527966-fdac0f44566c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60);
        position: sticky;
        padding-bottom: 3%;
        background-attachment: fixed;
       }

       .bg {
        background: rgba(255, 255, 255, 0.5);
       }

</style>

<main >
    <div class="bg">
    <h1>Services</h1>

    <div>
        <h3>No one wants to think about doing an estate plan. However, most everyone knows they need an estate plan. If you are contemplating taking that step and doing some planning, we can guide you through the process and make it as painless as possible. We have experience in many different issues related to estate planning, and we will be able to assist you in all of the following ways:</h3>
    </div>
<div class="row">
    <div class="right">
        <h2><a href="./BEPlanning">Basic Estate Planning</a></h2>                
        <p>Everyone needs a basic estate plan. A simple estate plan usually includes several core estate planning, documents. In our opinion, everyone needs a will, a power of attorney to manage assets, a medical power of attorney to manage health care, an advance directive to physicians (also known as a living will), and a HIPAA release to authorize disclosure of medical information.</p>
    </div>
    <img alt="papers" src="{papers}"  />
</div>

<div class="row">
        <img alt="house" src="{house}" />
    <div class="right">
        <h2>Advanced Estate Planning</h2>
        <p>Many clients can benefit from advanced estate planning tools to minimize probate expenses, increase privacy, and minimize estate taxation on death. Some tools that we use including revocable trusts, irrevocable trusts, special needs trusts, life insurance trusts, and grantor-retained annuity trust.</p>
    </div>
</div>

<div class="row">
    <div class="left">
         <h2><a href="./IPlanning">Incapacity Planning</a></h2>       
        <p>If you become incapacitated, it is imperative that you have an agent that is empowered to make financial and medical decisions on your behalf. A well drafted power of attorney for asset management and an updated health care directive is vital to your financial and personal well-being should you become incapacitated. We can help you prepare these documents so that they properly reflect your wishes.</p>
    </div>
    <img alt="hand" src="{hand}" />
</div>

<div class="row">
    <img alt="library" src="{library}" />
    <div class="right">
        <h2>Probate and Estate Administration</h2>
        <p>If property passes through a Will or if a person dies without a Will, then most estates must go through the court system.  When there is a will, we call that a probate administration.  When there is no will, we call an estate administration.  The attorneys at Willi Law Firm, P.C., handle probate and estate administrations in the central Texas area including Travis County, Williamson County, Hays County, Bastrop County, Blanco County, Burnet County, and Caldwell County.</p>
    </div>
</div>
<div class="row">
    <div class="left">
        <h2>Probate and Estate Litigation</h2>
        <p>Sometimes everyone does not agree. Is that an understatement for your family? In our experience, even the most level-headed persons can lose perspective when dealing with the loss of a family member. At Willi Law Firm, P.C., we make every attempt to help our clients work out disputes with family members. But when disputes cannot be resolved, we are ready to pursue all remedies. We handle probate and estate litigation in the central Texas area including Travis County, Williamson County, Hays County, Bastrop County, Blanco County, Burnet County, and Caldwell County.</p>
    </div> 
    <img alt="courtroom" src="{court}" />
</div>
    </div>
</main>