## Miről szól ez?

Kedves barátomnak, Vilinek készült, aki most tanulja a Javascript "rejtelmeit", hogy a gyakorló projektjében helyileg tudja futtatni az API-t anélkül, hogy regisztrálni kellene egy kulcsért egy fizetős szolgáltatónál.

---

## Használat

Egyszerű GET hívás a következő címre:

_http://localhost:3000/api/get?from=HUF&to=EUR_

**Paraméterek**:

- a **from** paraméter az induló pénznem,
- a **to** paraméter a cél pénznem.

A válasz példaként formátuma JSON:

```json
{
  "from": "EUR",
  "to": "HUF",
  "rate": 410
}
```

---

## Hogyan használd?

1. `git clone https://github.com/SGeri/fake-api.git`
2. `cd fake-api`
3. `npm install`
4. `npm run dev`
5. Használd egészséggel!
