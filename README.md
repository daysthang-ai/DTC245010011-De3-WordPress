# Đề tài 3: Website Quảng bá Sản phẩm (WordPress)
Hệ thống triển khai bằng Docker Compose:
- Ứng dụng: WordPress (PHP 8.2) + MySQL 8.0
- Reverse Proxy: Nginx (HTTPS tự ký, Security Headers)
- Giám sát: Prometheus, Grafana, cAdvisor, Node Exporter, MySQL Exporter, Blackbox Exporter
- Thu thập Log: Loki + Promtail

## Huong dan chay he thong
1. docker-compose up -d
2. Truy cap WordPress tai localhost:8080 hoac localhost:8443
