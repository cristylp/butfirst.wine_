# butfirst.wine_
Final project - Ironhack

## Wine routes


Base URL en la API para los vinos es "http://localhost:3000/api/wines", y utiliza los siguientes endpoints:

  | Path        | Method           | Description  |
  | ------------- | ------------- | ------------- |
  | `/getAllWines`  | GET | Muestra todos los vinos existentes  |
  | `/getOneWine/:wine_id` | GET | Muestra los detalles de un vino  |
  | `/newWine` | GET | Formulario para crear un nuevo vino  |
  | `/newWine` | POST | Guarda el nuevo vino creado |
  | `/editWine/:wine_id` | PUT | Edita un vino ya creado  |
  | `/deleteWine/:wine_id` | GET | Elimina de la BBDD un vino  |
  
  
  
  
## Users routes


 Utiliza los siguientes endpoints:

  | Path        | Method           | Description  |
  | ------------- | ------------- | ------------- |
  | `/user-zone/signup` | GET | Muestra el formulario para crear un usuario  |
  | `/user-zone/signup` | POST | Guarda en la BBDD un usuario  |
  | `/user-zone/login` | GET | Muestra el formulario para el Login del usuario  |
  | `/user-zone/login` | POST | Login del usuario a su perfil  |
  | `/user-zone/logout` | GET | Cierra la sesión del usuario  |
  | `/user-zone/profile` | GET | Muestra al usuario su perfil  |
  | `/user-zone/edit?user_id=xxx` | GET | Muestra el formulario para editar el perfil del usuario  |
  | `/user-zone/edit?user_id=xxx` | POST | Edita en la BBDD el perfil del usuario |
  | `/user-zone/delete` | GET | Muestra al ADMIN todos los perfiles de usuario |
  | `/user-zone/delete?user_id=xxx` | POST | Borra de la BBDD un usuario |
  



