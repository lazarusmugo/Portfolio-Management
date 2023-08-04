<script>
   //icons 
   import Icon from '@iconify/svelte';


    let userProfilePhoto = '1.png';
    let greeting = 'Good morning';

   
</script>
  
  <div class="flex items-center p-4">

     <img src={import.meta.url.replace('Home.svelte', userProfilePhoto)} alt="User Profile" class="w-10 h-10 rounded-full" />

    <div class="ml-2">
      <p>{greeting}  </p>
    </div>

    <Icon icon="twemoji:sun" class ="ml-2" />
  </div>

  <div class="text-4xl font-semibold mb-2 text-center">
    <h2 class = "welcome-section">Welcome</h2>
    <h2 class = "gradient-text "> ABOARD</h2>
</div>
<div>
    <p class="text-lg text-center">Welcome to our Portfolio Management dashboard,
        where managing your properties and
    tenants has never been easier!.</p>
</div>
    
  
  <div class="text-center mt-4">
   <div class = "inline-block">
     <button class="mt-4 bg-yellow-500 text-white py-2 px-4 rounded-lg flex items-center">
    <Icon icon="uil:plus" class="mr-2" />
    <span>Add Your Property</span>
 </button></div>
   
  </div>
  
  <style>
    .welcome-section {
        padding-top: 3rem;
        padding-bottom: 0.5rem;
      text-align: center;
    
    }
    .gradient-text {
        background: linear-gradient(to right, #13033e,#111ed4, #ffc507, #5134016a);    -webkit-background-clip: text;
    color: transparent;
    font-size: 2rem; 
    font-weight: 800;
    padding-bottom: 2rem;
 }

  </style>
  