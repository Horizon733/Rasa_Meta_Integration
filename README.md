<p align="center"><img src="./assets/bot.png" width="10%"></p>
<h1 align="center">Meta Integration Bot</h1>
<p align="center">Rasa assistant where I have demonstrated how to integrate with Instagram and Facebook</p>

## ⚡ Quick Setup
- Initialize a virtual environment via:
- Conda:
```bash
conda create --name rasaenv
```
- virtualenv
```bash
virtualenv rasaenv
```
- Install Rasa
```bash
python -m pip install -U pip
pip install rasa
```

## Fetching credentails for Facebook and Instagram
- Login/Create an account on Facebook
- Open [Developers for Meta](https://developers.facebook.com/) website
- Go to `My Apps`, create one by Clicking on `Create App`.
- Here, select `type` as `Business`
![screenshotr_2022-12-1T16-31-1](https://user-images.githubusercontent.com/57827233/205036319-d75dba9e-c19f-4d32-a71f-b41fba50ee3d.png)
- Add all details as you like for App name, contact-email, etc...
- Once you are on Dashboard, you will see products, as I already have setup them, you have to click on setup for `Messenger` product.
![screenshotr_2022-12-1T16-33-21](https://user-images.githubusercontent.com/57827233/205036767-2a4bf4d1-7f13-4648-8baa-3c07491e48e6.png)
- On your left side, Messenger section will appear.
  - Settings: Here, you can setup facebook messenger.
  - Instagram settings: Here, you can setup instagram messenger by connecting to your instagram page.
![image](https://user-images.githubusercontent.com/57827233/205037072-9d50e3fc-3581-4a05-b0ca-f8628798b7d0.png)
Note: Your page has to be connected with your Facebook account otherwise you won't see it.
