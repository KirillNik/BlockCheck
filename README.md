BlockCheck v0.0.9.6<br><br>
Для получения корректных результатов используйте DNS-сервер провайдера и отключите средства обхода блокировок.<br>

Проверка работоспособности IPv6: IPv6 недоступен.<br>
IP: 178.184.255.xxx, провайдер: Kemerovo Regional Telegraph, branch of Kuzbass Pub/ Ростелеком МРФ "Сибирь"<br>

[O] Тестируем IPv4 DNS<br>
	Через системный DNS:	 ['184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100', '95.167.13.50', '95.167.13.50']<br>
	Через Google DNS:	 ['104.20.134.45', '104.20.135.45', '104.24.10.70', '104.24.11.70', '184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100']<br>
	Через Google API:	 ['104.20.134.45', '104.20.135.45', '104.24.10.70', '104.24.11.70', '184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100']<br>
	Несуществующий DNS не вернул адресов (это не ошибка)<br>
[☠] DNS-записи подменяются<br>
[✓] DNS не перенаправляется<br>

[O] Тестируем HTTP (по настоящим IP-адресам сайтов)<br>
	Открываем  http://a.putinhuylo.com/<br>
[✓] Сайт открывается<br>
	Открываем  http://furry.booru.org/<br>
[✓] Сайт открывается<br>
	Открываем  http://furry.booru.org/index.php?page=post&s=view&id=111173<br>
[✓] Сайт открывается<br>
	Открываем  http://pbooru.com/<br>
[✓] Сайт открывается<br>
	Открываем  http://pbooru.com/index.php?page=post&s=view&id=303026<br>
[✓] Сайт открывается<br>
	Открываем  http://rutracker.org/forum/index.php<br>
[✓] Сайт открывается<br>

[O] Тестируем HTTPS<br>
	Открываем  https://e621.net/<br>
[✓] Сайт открывается<br>
	Открываем  https://lolibooru.moe/<br>
[✓] Сайт открывается<br>
	Открываем  https://rutracker.org/forum/index.php<br>
[✓] Сайт открывается<br>
	Открываем  https://www.dailymotion.com/<br>
[✓] Сайт открывается<br>

[!] Результат:<br>
[⚠] Ваш провайдер подменяет DNS-записи, но не перенаправляет сторонние IPv4 DNS-серверы на свой.<br>
 Вам поможет смена DNS, например, на Яндекс.DNS 77.88.8.8 или Google DNS 8.8.8.8 и 8.8.4.4.<br>
[⚠] Ваш провайдер полностью блокирует доступ к HTTPS-сайтам из реестра.<br>
[⚠] У вашего провайдера "обычный" DPI. Вам поможет HTTPS/Socks прокси, VPN или Tor<br>
![Image alt](https://github.com/KirillNik/BlockCheck/blob/master/1.png)
