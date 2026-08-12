// ==========================================
// ПЕРЕМЕННЫЕ
// ==========================================

let selectedFood = "";
let selectedActivity = "";
let selectedDate = "";
let selectedTime = "";

let noClicks = 0;


// ==========================================
// ПЕРЕКЛЮЧЕНИЕ ЭКРАНОВ
// ==========================================

function showScreen(number) {

    document
        .querySelectorAll(".screen")
        .forEach(screen => {
            screen.classList.remove("active");
        });

    document
        .getElementById("screen" + number)
        .classList.add("active");
}


// ==========================================
// КНОПКА "ДА"
// ==========================================

document
    .getElementById("yesButton")
    .addEventListener("click", function() {

        showScreen(2);

    });


// ==========================================
// КНОПКА "НЕТ"
// ==========================================

const noButton =
    document.getElementById("noButton");

const noText =
    document.getElementById("noText");


noButton.addEventListener("click", function() {

    noClicks++;


    const messages = [

        "Ты уверена? 🥺",

        "Попробуй ещё раз 😭",

        "Кнопка тоже хочет, чтобы ты нажала Да 💗",

        "Ну пожалуйстааа 🥹",

        "Кажется, кнопка убегает 😭",

        "Последний шанс! ❤️"

    ];


    noText.textContent =
        messages[
            Math.min(
                noClicks - 1,
                messages.length - 1
            )
        ];


    // Уменьшаем кнопку

    const scale =
        Math.max(
            0.35,
            1 - noClicks * 0.12
        );

    noButton.style.transform =
        `scale(${scale})`;


    // После нескольких нажатий
    // начинаем перемещать кнопку

    if (noClicks >= 2) {

        moveNoButton();

    }

});


// ==========================================
// ПЕРЕМЕЩЕНИЕ КНОПКИ
// ==========================================

function moveNoButton() {

    const buttons =
        document.querySelector(".buttons");

    const containerWidth =
        buttons.clientWidth;

    const containerHeight =
        buttons.clientHeight;


    const buttonWidth =
        noButton.offsetWidth;

    const buttonHeight =
        noButton.offsetHeight;


    const maxX =
        Math.max(
            0,
            containerWidth - buttonWidth
        );


    const maxY =
        Math.max(
            0,
            containerHeight - buttonHeight
        );


    const x =
        Math.random() * maxX;


    const y =
        Math.random() * maxY;


    noButton.style.position = "absolute";

    noButton.style.left = x + "px";

    noButton.style.top = y + "px";

}


// ==========================================
// ВЫБОР ЕДЫ
// ==========================================

document
    .querySelectorAll(".food")
    .forEach(card => {

        card.addEventListener("click", function() {

            document
                .querySelectorAll(".food")
                .forEach(item => {
                    item.classList.remove("selected");
                });


            this.classList.add("selected");


            selectedFood =
                this.dataset.value;

        });

    });


// ==========================================
// ПЕРЕЙТИ ПОСЛЕ ВЫБОРА ЕДЫ
// ==========================================

document
    .getElementById("foodNext")
    .addEventListener("click", function() {

        if (!selectedFood) {

            alert("Сначала выбери, что будем кушать 💗");

            return;
        }


        showScreen(3);

    });


// ==========================================
// ВЫБОР ЗАНЯТИЯ
// ==========================================

document
    .querySelectorAll(".activity")
    .forEach(card => {

        card.addEventListener("click", function() {

            document
                .querySelectorAll(".activity")
                .forEach(item => {
                    item.classList.remove("selected");
                });


            this.classList.add("selected");


            selectedActivity =
                this.dataset.value;

        });

    });


// ==========================================
// ПЕРЕЙТИ К ДАТЕ
// ==========================================

document
    .getElementById("activityNext")
    .addEventListener("click", function() {

        if (!selectedActivity) {

            alert("Сначала выбери, чем будем заниматься 💗");

            return;
        }


        showScreen(4);

    });


// ==========================================
// ВЫБОР ДАТЫ
// ==========================================

document
    .querySelectorAll(".date")
    .forEach(button => {

        button.addEventListener("click", function() {

            document
                .querySelectorAll(".date")
                .forEach(item => {
                    item.classList.remove("selected");
                });


            this.classList.add("selected");


            selectedDate =
                this.dataset.value;

        });

    });


// ==========================================
// ВЫБОР ВРЕМЕНИ
// ==========================================

document
    .querySelectorAll(".time")
    .forEach(button => {

        button.addEventListener("click", function() {

            document
                .querySelectorAll(".time")
                .forEach(item => {
                    item.classList.remove("selected");
                });


            this.classList.add("selected");


            selectedTime =
                this.dataset.value;

        });

    });


// ==========================================
// ФИНАЛ
// ==========================================

document
    .getElementById("finishButton")
    .addEventListener("click", function() {


        if (!selectedDate) {

            alert("Выбери дату 📅");

            return;
        }


        if (!selectedTime) {

            alert("Выбери время 🕐");

            return;
        }


        document
            .getElementById("resultFood")
            .textContent =
            "🍓 " + selectedFood;


        document
            .getElementById("resultActivity")
            .textContent =
            "✨ " + selectedActivity;


        document
            .getElementById("resultDate")
            .textContent =
            "📅 " + selectedDate;


        document
            .getElementById("resultTime")
            .textContent =
            "🕐 " + selectedTime;


        showScreen(5);

    });
