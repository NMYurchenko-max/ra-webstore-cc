# Страница интернет-магазина

![CI](https://github.com/NMYurchenko-max/ra-webstore-cc/actions/workflows/web.yml/badge.svg)

[deploy](https://nmyurchenko-max.github.io/ra-webstore-cc/)

## Задание

Необходимо создать React-компонент (class-based компонент)

[Task. ShopItemClass](https://github.com/netology-code/ra16-homeworks/blob/ra-51/components/store-class/README.md)

## Проект React+Vite

Getting Started: `yarn create vite my-app --template react`

Отличие компанента типа class от функционального компонента:

- class-based компоненты имеют доступ к жизненному циклу компонента (методы жизненного цикла)
- class-based компоненты могут иметь состояние (state)
Создается  extends от React.Component импортированного класса React
Отвлеченный Пример:
```JSX
This is a class-based component = class ShopItemClass extends React.Component {
  render() {
    return (
      <div className="shop-item">
        <img src={this.props.img} alt={this.props.name} />
        <h3>{this.props.name}</h3>
        <p>{this.props.price}</p>
      </div>
    );
  }
}
```
