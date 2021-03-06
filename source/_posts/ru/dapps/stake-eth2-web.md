---
title: "Стейкинг в Eth2 на MEW web"
date: 2018-06-01 00:02:00
tags:
  - staked.us
  - MEW
  - eth2
  - stake
categories:
  - 
    - dapps
primary_category: dapps
primary_category_display_name: "DАpps"
author: MyEtherWallet (MEW)
---

# **Стейкинг в Eth2 на MEW web**

###### {% read_time title "Stake on Eth2 using MEW web" %} мин. чтения

* * *

## **MEW интегрировал Staked.us для упрощения создания валидатора на Eth2 и получения процентного дохода.**

Как только вы сделаете ставку на Eth2 для создания валидатора, никаких дальнейших действий не требуется. Staked.us будет поддерживать и обновлять ваш валидатор для вас.

Чтобы создать валидатор, необходимо сделать ставку минимум 32 ETH. Ваша ставка будет находиться на Beacon Chain, которая лежит в основе Eth2. Для дополнительной информации об Eth2, Beacon Chain и создании валидатора, ознакомьтесь с нашей статьей о [0 Фазе Eth2][eth2].

**Вам также понадобится адрес для снятия Eth2.** Адреса снятия Eth2 используются для вывода вашей ставки ETH и накопленных процентов. Каждый пользователь получит адрес для снятия Eth2, файл-хранилище ключа и фразу восстановления для своей ставки на Eth2. Если вы сделаете ставку более 32 ETH, дополнительные валидаторы будут привязаны к одному и тому же адресу. Вы можете [генерировать свой собственный адрес для снятия Eth2][geneth2] в интерфейсе MEW web.

Когда вы генерируете адрес для снятия Eth2, вы введете пароль. Этот пароль привязан к файлу-хранилища ключа. Вы также получите фразу восстановления, которая в данном случае - список из 24 слов. Убедитесь, что вы записали эти слова правильно и храните их в безопасности.

Вы также можете [проверить ваш адрес снятия Eth2 ][geneth2] с помощью файла-хранилища ключа, чтобы убедиться, что все работает правильно.

**Не теряйте свой файл хранилище ключа Eth2 + пароль и фразу восстановления!** Они шифруют ваши ключи и необходимы для будущего доступа. Никто не может восстановить их для вас, поэтому очень важно хранить их в безопасности.

## **Риски стейкинга на Eth2**

<br>

Staked.us является провайдером интеграции стейкинг в MEW. Staked.us не будет иметь доступа к вашей ставке или заработанным процентам, но будет нести ответственность за поддержку вашего валидатора. Если валидатор не выполняет свою работу в течении длительного периода времени, **существует риск того, что ваша ставка ETH будет оштрафована**. Таким образом, ваша ставка находится в руках Staked.us.

Кроме того, вся ставка ETH и годовые проценты от вашего валидатора не смогут быть сняты до более поздней фазы Eth2. Точная дата когда эта фаза войдет в силу пока неизвестна. Очень важно, чтобы вы понимали: все ставки ETH сделанные на стадии 0 будут недоступны для вывода до тех пор, пока транзакции Eth2 не станут возможны на более позднем этапе.

### **Стейкинг на Eth2 с помощью MEW web**

<br>

**Шаг 1.** Откройте кошелек в [MEW веб][mew] через ваш обычный метод доступа. Если вы используете приложение MEW wallet, вы можете [делать стейкинг на Eth2 непосредственно из приложения][mwstake].

<img src="/images/posts/diving-deeper/stake1.png" width="85%" />

**Шаг 2.** Зайдите в раздел 'DАpps' и выберите 'Staked’.

<img src="/images/posts/diving-deeper/stake2.png" width="50%" />

**Шаг 3.** Введите или выберите количество ETH кратное 32. Для каждой ставки 32 ETH, Staked.us создаст для вас один валидатор.

<img src="/images/posts/diving-deeper/stake3.png" width="85%" />

**Шаг 4.** Загрузите файл хранилище ключа Eth2 который вы получили при создании адреса снятия Eth2.

<img src="/images/posts/diving-deeper/stake4.png" width="85%" />

**Шаг 5.** Просмотрите информацию о вашей ставке и проверьте адрес снятия Eth2. Затем выберите Активировать стейкинг.

<img src="/images/posts/diving-deeper/stake5.png" width="85%" />

**Шаг 6.** Создание валидаторов займет от нескольких секунд до нескольких минут. После этого вы можете нажать на Стейкинг в Eth2 для подтверждения транзакции и завершения процесса стейкинга.

<img src="/images/posts/diving-deeper/stake6.png" width="85%" />

<img src="/images/posts/diving-deeper/stake7.png" width="85%" />

**Шаг 7.** Ваш валидатор теперь готов к работе в Eth2, но для его внедрения может потребоваться 48 часов. Вы можете просмотреть вашу транзакцию на Etherscan. Staked.us будет поддерживать и обновлять ваш валидатор(ы), так что вам остается только получать годовые проценты.

<img src="/images/posts/diving-deeper/stake9.png" width="85%" />

[eth2]: /@@@@@@/diving-deeper/what-is-staking-eth2/

[geneth2]: /@@@@@@/diving-deeper/eth2-address/

[geneth2]: /@@@@@@/diving-deeper/eth2-address/

[mew]: https://www.myetherwallet.com

[mwstake]: /@@@@@@/mewwallet/stake-eth2-mw/
