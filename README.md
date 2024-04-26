# SpeedTest
Monitoração Teste de velocidade - SpeedTest<br>

_________Instalação_________

cd /tmp/<br>
wget -O speedtest-cli https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py<br>
chmod +x speedtest-cli<br>
vim /etc/crontab<br>
*/10 *  *  *  *  root /usr/bin/python3.9 /tmp/speedtest-cli --json > /tmp/speed.log<br>
