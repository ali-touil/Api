# Se connecter à l'API REST DSN

L'API DSN est l'interface qui permet au logiciel de paie du déclarant de s'authentifier directement auprès du point de classement des déclarations sociales nominatives sans avoir à accéder au site Web net-entreprises.fr pour déposer et consulter ses déclarations.

# Authentification

Cette fonction prend en paramétres quatre arguments: 
- Numéro de siret de la société
- Nom et le prénom du déclarant
- Mot de passe du compte NET-Entreprise

```php
public function DSN($siret, $lastname, $firstname, $password)
{
  // Some code
}
```
