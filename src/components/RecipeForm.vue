<script setup>

</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-lg-4">
                <form>
                    <div class="mb-3">
                        <input type="text" class="form-control" placeholder="Keress receptet...">
                    </div>
                </form>
            </div>
            <div class="col-lg-4">
                <select class="form-select">
                    <option value="1" selected>Minden nehézség</option>
                    <option value="2">Könnyű</option>
                    <option value="3">Közepes</option>
                    <option value="4">Nehéz</option>
                </select>
            </div>
            <div class="col-lg-4">
                <select class="form-select" aria-label="Default select example">
                    <option value="1" selected>Elkészítési idő szerint</option>
                    <option value="2">Nehézség szerint</option>
                </select>
            </div>
        </div>
    </div>
</template>

<style scoped></style>