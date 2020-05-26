# cordova-angular-refresh-problem

Note: on windows use gitbash

### Setup
bash setup.sh

### Run Cordova
npm run cordova

### To reproduce
- Click on HTTP Call, it will stay on 'LOADING'
- Click toggle twice, this will force angular refresh, you will see REFRESH DONE

### Run Web Version
npm run web (it will open a browser)

### Normal behavior
- Click on HTTP Call, it will stay on 'LOADING' then 'REFRESH DONE'
- Click toggle twice will show no difference, as it was already refreshed by zone
