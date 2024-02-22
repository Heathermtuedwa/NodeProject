<template>
    <div class="landing page">
    <div class="content">
        <div class="container-2">
              <h1 class="animated-heading">H & S SkinCare</h1>
        </div>
            <div class="container">
                <img src="https://i.postimg.cc/9QRDmmD9/Getty-Images-637130628-1-scaled.webp" alt="Description of image" class="image-small">
            </div>
          </div>
        </div>
</template>

<script>

</script>


<style scoped>
* {
    box-sizing: border-box;
}



a {
    text-decoration: none;
}

ul {
    list-style: none;
    padding: 0;
    margin: 0;
}


.content {
    display: flex;
    flex-direction: column;
    align-items: center;
} 

.image-small {
    max-width: 70%; 
    height: auto; 
    display: block;
    margin-left: auto; 
    margin-right: auto;
}

.container-2 {
 text-align: center;
 font-size: 30px;
  color: rgb(239, 89, 89);
}

.animated-heading {
  animation: slideIn 2s ease infinite alternate; 
}


@keyframes slideIn {
  0% {
    transform: translateY(-10px); 
    opacity: 0; 
  }
  100% {
    transform: translateY(0); 
    opacity: 1; 
  }
}
</style>
