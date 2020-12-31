query {
  weatherByCity(city: "Istanbul") {
    id
    base
    weather {
      id
      main
      description
    }
  }
}
