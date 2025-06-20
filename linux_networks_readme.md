# Сети в Linux

## _Настройка сетей в Linux на виртуальных машинах_

**Описание:** Изучение сетевых технологий Linux через настройку маршрутизации, firewall и сетевых сервисов. Построение многоуровневой сетевой топологии с маршрутизаторами, настройка DHCP, NAT и SSH туннелей.

## Основные части проекта

**Part 1. Инструмент ipcalc**
Расчет сетевых адресов, масок подсетей. Определение диапазонов localhost, публичных и частных IP-адресов.

**Part 2. Статическая маршрутизация между двумя машинами**
Настройка сетевых интерфейсов и маршрутов между двумя виртуальными машинами.

**Part 3. Утилита iperf3**
Измерение скорости сетевого соединения между машинами.

**Part 4. Сетевой экран**
Настройка iptables с различными стратегиями фильтрации. Использование nmap для сканирования сети.

**Part 5. Статическая маршрутизация сети**
Построение сетевой топологии с 5 машинами (3 рабочие станции, 2 роутера). Настройка IP-переадресации и статических маршрутов.

**Part 6. Динамическая настройка IP с помощью DHCP**
Настройка DHCP сервера для автоматического назначения IP-адресов. Привязка адресов к MAC.

**Part 7. NAT**
Настройка Network Address Translation для доступа внутренней сети к внешним ресурсам. SNAT и DNAT правила.

**Part 8. SSH Tunnels**
Создание локальных и удаленных SSH туннелей для безопасного доступа к сервисам.

## Технологии

- Ubuntu 20.04 Server LTS
- VirtualBox
- iptables
- isc-dhcp-server
- Apache
- SSH