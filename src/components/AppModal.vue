<template>
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Человек-паук</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <img src="http://i.annihil.us/u/prod/marvel/i/mg/3/50/526548a343e4b.jpg"
                        alt="Человек-паук" style="max-width: 100%;">

                    <div>
                        <p class="text-muted">2020-07-21T10:30:10-0400</p>
                        <h5>Описание:</h5>
                        <p>
                            Укушенный радиоактивным пауком,
                            старшеклассник Питер Паркер обрел 
                            скорость, силу и силу паука. Приняв имя 
                            Человек-паук, Питер надеялся начать карьеру, 
                            используя свои новые способности. Наученный тому, 
                            что с большой силой приходит большая ответственность, 
                            Паук поклялся использовать свои силы, чтобы помогать людям.
                        </p>

                        <h5>Комиксы:</h5>

                        <ul>
                            <li>Adventures of Spider-Man (1996) #1</li>
                            <li>Adventures of Spider-Man (1996) #2</li>
                            <li>Adventures of Spider-Man (1996) #3</li>
                        </ul>
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "AppModal",
    }
</script>

<style scoped>

</style>
