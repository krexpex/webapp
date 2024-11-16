// Примерный код игрового интерфейса
const tg = window.Telegram.WebApp;

tg.expand();

function playCard() {
    // Здесь будет логика отправки карты
    tg.sendData("played_card");
}

tg.onEvent("mainButtonClicked", () => {
    tg.sendData("end_turn");
});
