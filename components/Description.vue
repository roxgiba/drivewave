<script>
import card_img1 from "@/assets/card_img1.png";
</script>

<template>
  <div class="description">
    <h2>RV rentals from the outdoor company</h2>
    <p>
      Sit under the star-filled sky, watch the sunrise from your bed, and get
      closer to what really matters. Book your RV or camper van with roadsurfer
      today and start planning your next adventure.
    </p>

    <div class="card_container">
      <div class="card">
        
        <h3>Enjoy More Freedom with One-Way RV Rentals!</h3>
        <img :src="card_img1" alt="Card Image 1" />
        <p>
          Did you know that our RV rentals in North America can also be booked
          as a convenient one-way option? Save time and distance, while
          enjoying maximum flexibility to create even more unforgettable
          moments on your road trip adventure!
        </p>
        <button>Book now</button>
      </div>

      <div class="card">
        
        <h3>New Locations Opening Spring 2024!</h3>
        <img :src="card_img1" alt="Card Image 1" />
        <p>
          We're thrilled to announce that we're taking our adventure to three
          new countries and locations in the upcoming year. Our exciting new
          camper van and RV rental locations will be open in Canada, Ireland,
          and Norway as well as various locations across existing countries in
          Europe! And in the US, we're opening in San Francisco and Las Vegas!
        </p>
        <button>Book now</button>
      </div>
    </div>

    <hr />

    <h2>Our newest locations</h2>
    <p>
      Find the perfect destination to start your road trip with an RV. Our
      newest locations are bookable now for trips starting in spring 2024!
    </p>
  </div>
</template>

<style>
.description {
  margin: 60px auto;
  text-align: center;
  line-height: 30px;
  font-family: "Encode Sans", sans-serif;
  margin-bottom: 20px;
}

p{
  margin: 20px
}

.card_container {
  display: flex;
  justify-content: space-around;
  font-family: "Encode Sans", sans-serif;
}

.card {
  padding: 10px;
  border: 1px solid black;
  width: 30%; /* Adjust the width as needed */
  box-sizing: border-box; /* Include padding in the width calculation */
  margin: 40px;
}

.card img {
  width: 100%; /* Make the image fill the container */
  height: auto; /* Maintain the aspect ratio */
}
</style>