<template>
<!-- Form Starts Here -->
    <div class="container-flex">
        <form class="data-entry-form row">
            <div class="form-group">
                <label for="id-entry" class="label-config">Enter ID</label>
                <input type="id" class="form-control">
            </div>

            <div class="form-group">
                <label for="id-entry" class="label-config">Enter Name</label>
                <input type="id" class="form-control">
            </div>

            <div class="form-group">
                <label for="id-entry" class="label-config">Enter Image URL</label>
                <input type="id" class="form-control">
            </div>
        </form>
    </div>
</template>

<script>

</script>

<style>
.container-flex{
    width: 100vw;
    height: 100vh;
    margin-top: 15px;
    margin-bottom: 15px;
    margin-left: 10px;
    margin-right: 10px;
}

.form-group{
    margin-top: 15px;
    margin-bottom: 15px;
    display: flex;
    text-align: left;
    align-items: center;
}

.label-config{
    height: 30px;
    width: 160px;
    font-weight: bold;
}

.form-control{
    margin-left: 30px;
    height: 50px;
}
</style>