1. Basic info:
The API I wrote is to view the Weather API. This is an API provided by weatherbit. IO that provides a key and corresponding information to get real-time weather information about a place or weather related information like air quality.


2. Base URL:
HTTP: http://api.weatherbit.io/v2.0/current
HTTPS: https://api.weatherbit.io/v2.0/current
Supported Methods: GET


3. Request Parameters:  
    >3.1 key=[key] (REQUIRED)  
        `` 
        key - Your API Key.
        ``

    >3.2 lang=[language](optional)  
    >>
        ``
        en - [DEFAULT] English  
        ar - Arabic  
        az - Azerbaijani  
        be - Belarusian  
        bg - Bulgarian  
        bs - Bosnian  
        ca - Catalan  
        cz - Czech  
        da - Danish  
        de - German  
        fi - Finnish  
        fr - French  
        el - Greek  
        es - Spanish  
        et - Estonian  
        ja - Japanese  
        hr - Croation  
        hu - Hungarian  
        id - Indonesian  
        it - Italian  
        is - Icelandic  
        iw - Hebrew  
        kw - Cornish  
        lt - Lithuanian  
        nb - Norwegian Bokmål  
        nl - Dutch  
        pl - Polish  
        pt - Portuguese  
        ro - Romanian  
        ru - Russian  
        sk - Slovak  
        sl - Slovenian  
        sr - Serbian  
        sv - Swedish  
        tr - Turkish  
        uk - Ukrainian  
        zh - Chinese (Simplified)  
        zh-tw - Chinese (Traditional) 
        `` 
  
    >3.3 units=[units](optional)
        M - [DEFAULT] Metric (Celcius, m/s, mm)
        S - Scientific (Kelvin, m/s, mm)
        I - Fahrenheit (F, mph, in)


4. API Endpoints
    | Description                              | Required Parameters |
    | :--------------------------------------- | :------------------ |
    | Get observation by lat/lon (Recommended) | lat,lon             |
    | Get observation by city name             | city, state(optional), country (optional) |
