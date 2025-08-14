# 1. Install deps for root

npm install

# 2. Install deps for example

cd example
npm install

# 3. Go back to root and link locally

cd ..
npm run build

# 4. Run example

cd example
npm run dev

# npm publish

npm run build
npm login
npm publish --access public

```
let obj = {
API_URL: "http://localhost:4013/",
MAP_DATA: "http://localhost:4013/gis/wms",
isProduction: false,
layersJsonDefault: layersJsonDefault,
INDIA_CENTER_COORDS: [77.2154, 28.6285],
INITIAL_ZOOM: 13,
showLatLon: true,
freezeMap: false,
KEY: "",
URL: "<<URL>>/wms/{z}/{x}/{y}",
handleChildCallback: (data: string) => {
console.log("Data received from child:", data);
},
};
 <MAP obj={obj} />
```
# Bisag_MAP
