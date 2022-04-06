# Vstack
VStack é um projeto baseado em Larasail com o objetivo de realizar o deploy de novos droplets ou instâncias da VPN de forma fácil e segura. Para utilizar, basta clonar o repositório abaixo em uma instância **Ubuntu**. Recomenda-se que instância esteja formatada e criada em modo texto (testado no **Ubuntu 20**).

```
sudo curl -sL https://github.com/pedroroccon/vstack/archive/main.tar.gz | tar xz && source vstack-main/install
```

Após clonar o repositório, rode o comando
```
vstack setup
```