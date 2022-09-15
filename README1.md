changes for production deployment 

file name index.js  root file
  1.change base url and BASE_IMG_URL
      // export const BASE_URL = "http://18.191.133.56/valetparking-api";
      // export const BASE_IMG_URL = "http://18.191.133.56/valetparking-api";

      to this
      export const BASE_URL = "https://flixvalet.com/api";
      export const BASE_IMG_URL = "https://flixvalet.com/api";
         
 2. change SUB_DIRCTORY
      // export const SUB_DIRCTORY = "/valetparking-admin";
      to this
      export const SUB_DIRCTORY = "/admin";


file name package.json
  change - "homepage": "https://flixvalet.com/admin"
            to this
            change "homepage": "/valetparking-admin"


file name index.html
  change- href="%PUBLIC_URL%/valetparking-admin/favicon.ico"
          to this
          change href="%PUBLIC_URL%/admin/favicon.ico"