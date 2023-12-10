<div style="background-color: #ADD8E6; color: white; padding: 20px; text-align: center;">
  <h1 style="display: inline;">Lean Mean Pet Feeding Machine 🐾 </h1>
</div>
  
### What is this and why does it exist?
In response to the alarming statistic that 60% of pet dogs and cats suffer from obesity, we created Lean Mean Pet Feeding Machine. This innovative mobile app empowers pet owners to accurately determine the right amount of food and feeding schedules for their furry companions, promoting optimal pet health.

### Usage
![login](/images/login.png)

Login page for logging in.

![register](/images/signup.png)

Make a new account.

![petlist](/images/new-petlist.png)

Home page listing your pets.

<div style="display: flex; justify-content: space-around;">
    <img src="/images/pet-info-pt1.png" alt="Schedule Page" style="width: 400px;">
    <img src="/images/pet-info-pt2.png" alt="Meal Editor" style="width: 400px;">
</div>

A detailed view of a specific pet's information. Like their BCS score to get a gauge on their healthy weight.

<div style="display: flex; justify-content: space-around;">
    <img src="/images/schedule-page.png" alt="Schedule Page" style="width: 400px;">
    <img src="/images/meal-editor.png" alt="Meal Editor" style="width: 400px;">
</div>
Schedule used to keep track of feeding times.

![vet](/images/vetchat.png)

Send messages to registered vets and they can answer.

![forum](/images/forum-page.png)

Forum where you can have discussions with other users.

<div style="display: flex; justify-content: space-around;">
    <img src="/images/image-selection.png" alt="Food Catalog" style="width: 400px;">
    <img src="/images/catalog-form.png" alt="Meal Editor" style="width: 400px;">
</div>

A page that informs you if your current food is appropriate for your pet and lists other options. It allows the user to select their pet's nutrition label from their gallery and extracts the necessary nutrients. The user has the option to edit and submit the nutrition form as well.

<div style="display: flex; justify-content: space-around;">
    <img src="/images/settings.png" alt="Setting Page" style="width: 300px;">
    <img src="/images/light-theme.png" alt="Light Theme" style="width: 300px;">
    <img src="/images/dark-theme.png" alt="Dark Theme" style="width: 300px;">
</div>

Settings tab that allows you to modify settings for your account. User is able to choose between the light and dark theme.


### Installation
```
git clone https://github.com/Lean-Mean-Pet-Feeding-Machine/pet-feeder.git
cd pet-feeder
flutter run
```
## Deployment
The application is currently deployed on Firebase App Distribution.
[Download Android App](https://appdistribution.firebase.google.com/testerapps/1:447694894462:android:771fcf5f47c2c25f556f2f/releases/3g7ga8a2g12e0?utm_source=firebase-console)

### Development Status
[Project Board](https://github.com/orgs/Lean-Mean-Pet-Feeding-Machine/projects/2)

[**Evaluation Report**](evaluation.md)

### Members
[Silvia De Benedictis](https://www.linkedin.com/in/silvia-debenedictis)
* Contributions: Created the Sign-up, Pet List, Schedule, My Vet, and Forum mock-up pages. Implemented authorization workflow, where user can login with an existing account and log out using the side menu bar. Also implemented Schedule page to add or modify the pet's feeding times. Other features that were implemented include the search bar on the forum page and the image to text feature on the food catalog page.

[Trey Yasunaga](https://github.com/yertsti)
* Contributions: