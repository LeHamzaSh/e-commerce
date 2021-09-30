<template>
<!-- Form Starts Here -->
    <div class="container-flex">
        <form class="data-entry-form row">
            <h1 class="heading-title">Add New Items Form</h1>
            <div class="form-group">
                <label for="id-entry" class="label-config">Enter ID</label>
                <input type="id" class="form-control" placeholder="Enter Id for the item" required>
            </div>

            <div class="form-group">
                <label for="name-entry" class="label-config">Enter Name</label>
                <input type="id" class="form-control" placeholder="Enter Name for the item" required>
            </div>

            <div class="form-group">
                <label for="image-entry" class="label-config">Enter Image Url</label>
                <input type="id" class="form-control" placeholder="Enter Image Url for the item" required>
            </div>

            <div class="form-group">
                <label for="image-entry" class="label-config">Enter Quantity</label>
                <input type="id" class="form-control" placeholder="Enter Quantity for the item" required>
            </div>

            <div class="form-group justify-content-center">
                <select class="custom-select" required>
                    <option value=""  class="value">Choose Category</option>
                    <option value="1" class="value">Fruit</option>
                    <option value="2" class="value">Vegetable</option>
                </select>
            </div>
        </form>
    </div>
</template>

<script>

</script>

<style>

.form-group{
    margin-top: 15px;
    margin-bottom: 15px;
    margin-left: 10px;
    display: flex;
    text-align: left;
    align-items: center;
}

.label-config{
    height: 30px;
    width: 160px;
    font-weight: bolder;
    color: whitesmoke;
    font-size: 14pt;
}

.form-control{
    height: 50px;
    width: 80vw;
    background-color: transparent;
    text-align: center;
}

.data-entry-form{
    width: 100vw;
    margin-top: 10px;
    margin-bottom: 10px;
    font-family: cursive;
}

.heading-title{
    color: whitesmoke;
    font: italic;
    font-weight: bold;
}

.custom-select, .value{
    background-color: lightgray;
    color: darkred;
    width: 50%;
    font-weight: bold;
    font-size: 15pt;
}

form .form-control::-webkit-input-placeholder { 
  color: yellow;
}

form .form-control::-moz-placeholder {
  color: yellow;
}
form .form-control:-ms-input-placeholder {
  color: yellow;
}
form .form-control:placeholder {
  color: yellow;
}

</style>