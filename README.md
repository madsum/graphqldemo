http://localhost:8080/gui

{
  foods {
    id
    name
    isGood
  }
}

{ food(id: 1) { name } }

mutation {
  saveFood(food: { name: "Pasta" }) {
    id
    isGood
  }
}