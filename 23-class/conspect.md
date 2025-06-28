
### Классы
Класс: много Функциональный Шаблон Для Создания Обьектов

getter: специальный метод для получения значения каковото свойства
setter: метод для устоновления значения какомуту свойству
firstStudent.sity = "Москва"

set city(value) {
  const firstLetter = value[0].toUpperCase();
  const fromSecondLetter = value.slice(1).toLowerCase();
  this._city() = `${firstLetter}${fromSecondLetter}`
}
get city() {
  return `г. ${this._city}`
}
ключевое слово static
