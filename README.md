# nft_token

В данном проекте реализована возможность создания NFT токенов и выставление их на продажу. Продажа доступна только владельцу. Реализована проверка, на то, чтобы имя токена было уникальным и содержало хотя бы 1 символ в названии.

### Установка
<code>tondev sol compile NftToken.sol</code>
<br>
<code>tondev c d NftToken -v 1234567890</code>
<br>


### Функционал
Создание нового токена:
<code>tondev c r NftToken createToken</code>
<br>
Предложить токен на продажу:
<code>tondev c r NftToken offerTokenForSale</code>
<br>
Получить информацию по указанному токену:
<code>tondev c r NftToken getToken</code>
