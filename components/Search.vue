<script></script>

<template>
  <main>
    <section class="toggle">
      <!-- Toggle buttons -->
      <button class="white">RV Rentals</button>
      <button class="yellow">Camping Spots</button>

      <!-- Search inputs for station and date -->
      <div class="form-container">
        <h1>Camper & RV Rentals</h1>
        <p>Book your next adventure today!</p>
        <div class="fields">
          <fieldset>
            <legend>Station</legend>
            <label
              ><input id="station" name="station" placeholder="Please Select"
            /></label>
          </fieldset>
          <fieldset>
            <legend>Period</legend>
            <label
              ><input id="period" name="period" placeholder="From - to"
            /></label>
          </fieldset>
          <button class="search">Search</button>
        </div>
      </div>
    </section>
  </main>
</template>

<style>
main {
  background-image: url("@/assets/imgUrl.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  width: 100%;
  height: 600px; /* Make it cover the entire viewport height */
  display: flex;
  justify-content: center; /* Center the content horizontally */
  align-items: center; /* Center the content vertically */
}

.form-container {
  width: fit-content; /* Adjust the width of the section */
  padding: 10px;
  padding-top: 5px;
  background-color: rgb(
    255,
    255,
    255
  ); /* Add a semi-transparent background to improve visibility */

  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  border-top-right-radius: 10px;
}

/* Rest of your styles */
.fields {
  display: flex;
  gap: 10px;
  width: 80%;
}
/* Responsive adjustments */
@media screen and (max-width: 600px) {
  .fields {
    flex-direction: column; /* Stack fieldsets vertically on smaller screens */
  }
}

.toggle {
  margin-right: 5px;
  padding: 5px;
}

.white {
  background-color: white;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  border: none;
  padding: 10px;
  margin-right: 5px;
}

.yellow {
  background-color: orange;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  border: none;
  padding: 10px;
}

input {
  border: none;
  width: 300px;
}

.search {
  background-color: #6bbbae;
  border: none;
  border-radius: 7px;
  width: 100%;
  color: white;
  padding: 2px;
  font-weight: 700;
  font-size: 16px;
  height: inherit;
  padding: 13px;
  place-self: center;
}
/* Add any additional styling as needed */
</style>
