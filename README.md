# Hi there 👋 I'm Camilo Poma!

[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/CamiloPZ)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/camilo-d-vinchi-poma-zamudio-142711139/)
[![Instagram](https://img.shields.io/badge/-Instagram-c13584?style=flat&labelColor=c13584&logo=instagram&logoColor=white)](https://www.instagram.com/camilo_poma/)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:cpomaz@uni.pe)
<!-- [![Outlook](https://img.shields.io/badge/-Outlook-0078D4?style=flat&logo=Microsoft-Outlook&logoColor=white)](mailto:murillo_comino@hotmail.com) -->

&nbsp;
![dash](https://user-images.githubusercontent.com/50030481/118587176-be754800-b761-11eb-9bdd-7756b19da388.PNG)

## :boy: **Talking about Personal Stuffs:**

- 🔭 I’m currently working on Instance Segmentation and Non Supervised Learning
- 💬 Ask me about data visualization with python
- ⚡ Fun fact: Data Analysis

## :computer: A little bit of my dash code

```python

import dash
import dash_bootstrap_components as dbc
import vaex as vx

df = vx.open('data_github.parquet')

app = dash.Dash(
    __name__,
    suppress_callback_exceptions=True,
    title="Dash Me",
    external_stylesheets=[dbc.themes.DARKLY],
    meta_tags=[
        {
            "name": "viewport",
            "content": "width=device-width, initial-scale=1.0, maximum-scale=1.2, minimum-scale=0.7",
        }
    ],
)
server = app.server


if __name__ == '__main__':
    app.run_server(debug=True)

```

See you!

<!-- You can e-mail me directly, get in touch through the account(s) below! -->


<!--
**CamiloPZ/CamiloPZ** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...

- 📫 How to reach me: ...
- 😄 Pronouns: ...

-->
