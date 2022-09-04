# 📡 Usar a API

## :pencil: Requisitos

#### Obter o token

Para obter o seu token use o comando [api](../suporte/comandos/api.md).

## Começar

<figure><img src="../.gitbook/assets/insomnia-discloudapi-user.png" alt=""><figcaption></figcaption></figure>

### Comece a usar a API

{% code title="Shell" %}
```shell
curl --request GET \
  --url https://api.discloud.app/v2/user \
  --header 'api-token: DISCLOUD_TOKEN'
```
{% endcode %}

{% hint style="info" %}
Renomeie `DISCLOUD_TOKEN` com o seu token
{% endhint %}

Você pode importar o código a cima em aplicativos como o [Insomnia](https://insomnia.rest/download) ou [Postman](https://www.postman.com/downloads/), e a partir deles testar e gerar códigos para a linguagem que desejar

> Exemplos:

{% tabs %}
{% tab title="Insomnia" %}
<div>

<figure><img src="../.gitbook/assets/insomnia-generate-code.png" alt=""><figcaption><p>1</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/insomnia-code.png" alt=""><figcaption><p>2</p></figcaption></figure>

</div>


{% endtab %}

{% tab title="Postman" %}
<div>

<figure><img src="../.gitbook/assets/postman-generate-code.png" alt=""><figcaption><p>1</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/postman-code.png" alt=""><figcaption><p>2</p></figcaption></figure>

</div>
{% endtab %}
{% endtabs %}
