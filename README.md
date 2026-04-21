
**Sophos Firewall Zabbix Template**

Bộ template Sophos Firewall SFOS v22 cho Zabbix 7.0 LTS trở lên.


**🚀 Tính năng chính**

Template này sử dụng SNMP để thu thập dữ liệu và cung cấp các giám sát chi tiết sau:

- Chỉ số thiết bị (System Health)

- Giám sát Memory (RAM) và Storage (Disk usage)

- Thời gian hoạt động (Uptime)

- Traffic của Port (Interface Statistics)

- Trạng thái IPsec VPN

- License thiết bị

**⚙️ Hướng dẫn cài đặt**

***1. Import Template:***

- Tải file template_sophos_xgs_firewall_version_22.yml.

- Trong Zabbix Web UI, đi tới Data collection > Templates > Import.

***2. Gắn Template vào Host:***

- Tạo hoặc chọn Host đại diện cho thiết bị Sophos Firewall.

- Trong phần Templates, thêm template Sophos XGS Firewall SNMP.
