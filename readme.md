# Mock de recursos site vue axios

Nesse repositório você vai encontrar variáveis CSS, mocks de APIs e arquivos de imagens necessários para a implementação do frontend.

___________________

## Variáveis CSS

Para facilitar a implementação das cores no projeto, seguem abaixo as variáveis CSS com o esquema de cores do front:
```css
:root {
  --color-background:#F3F3F3;
  --color-background-nav:#2B3D50;
  --color-background-home:#344960;
  --color-text-light:#EDEDED;
  --color-text-title:#FF5555;
  --color-text-dark:#3D3D3D;
}
```

___________________

## Imagens

* **Logo WDEV:**  
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg
```

* **Inscreva-se:**
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg
```

* **Menu Mobile:**
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg
```

As imagens das redes sociais estarão disponíveis no response da API de `GET /social-links.json`;
___________________

## Mocks de APIs

Esse repositório será o endpoint das APIs do front, então é necessário configurar a seguinte URL como base:
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/api
```

A partir dessa URL teremos os seguintes recursos:
* **Redes sociais** `GET /social-links.json`
* **Vídeos** `GET /videos.json`
* **Sobre** `GET /about.json`
* **Contatos** `GET /contacts.json`

___________________
