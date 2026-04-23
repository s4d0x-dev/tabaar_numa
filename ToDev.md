## Data insertion:
  - insert data inside `[]`'s after `return` inside data function, like:
      - ```javascript
        function data() {
         return [
         {
           "id": "0",
           "rels": {
             "spouses": [
               "33f7b359-32d3-47cb-b989-bfafb3544cb9"
             ],
             "children": [
               "37f0a29d-a4f5-416a-a2c6-719f1b74478e",
               "cf158fb8-200c-4397-8046-8eef01a4920e",
               "1fed1985-ee17-4d6f-9417-659df4311393"
             ]
           },
           "data": {
             "first name": "آقای بابا بزرگ",
             "last name": "هرچه",
             "birthday": "1300",
             "avatar": "https://static8.depositphotos.com/1009634/988/v/950/depositphotos_9883921-stock-illustration-no-user-profile-picture.jpg",
             "gender": "M",
             "note": "مرد با ایمان و فرزند دوست",
             "alive": "نه",
             "study field": "پزشکی",
             "study grade": "14"
           }
         },
      ```

## Selecting a Field to view:
### Making viable to Side-Menu:
- just simply add field name (from data) to `.setFields` method, like:
  - ```javascript
    .setFields(["first name","last name","birthday","alive"])
    ```
### Making viable to Card-Display:
  - just simply add field name (from data) to `.setCardDisplay` method, like:
    - ```javascript
      .setCardDisplay(["first name","last name","birthday","alive"])
      ```