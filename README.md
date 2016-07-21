# strava-leaderboard

Compare yourself with people you follow on starred segments.

## to config
```
git clone https://github.com/tszpinda/strava-leaderboard
cd strava-leaderboard
mkdir -p data
echo '
{                                                                
  "access_token"    :"check-starva"
  , "client_id"     :"check-starva"
  , "client_secret" :"check-starva"
  , "redirect_uri"  :"http://localhost:3000/auth-ok"
}
'
```

## to run
```
npm install
node app.js
```
