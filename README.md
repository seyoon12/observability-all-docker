# Docker Observability Stack
TEMPO, LOKI,MIMIR, MINIO 등 분산 아키텍처로 구성하여 데이터 복제 및 장애 조치를 지원합니다.
로그의 수집, 저장, 조회, 역할을 개별적으로 분리하여 부하를 효과적으로 분산하고 특정 컴포넌트에 과부화가 집중되지 않으며 확장성 있게 설계되었습니다.

### includes:
- **Prometheus**
- **Grafana**
- **Loki**
- **Tempo**
- **Mimir**
- **Alertmanager**
- **Node-exporter**
- **snmp-exporter**
- **wmi-exporter**
- **my-sqld-exporter**
- **nxlog**
- **promtail**
- **fluentd**
- **blackbox**
- **open-telemetry-collector**
- **open-telemetry-collector**

### 참고 사항
기존에 사용했던 config와 동일하게 작성 시 해당 아키텍처의 중요 데이터 (예시: IP, API KEY) 등이 노출되기에 수정하였습니다.


### Distributed 구조
<img src="https://github.com/user-attachments/assets/d21aa0fa-5f99-40f7-a26f-4883fd164dd1" width="1200">

### Linux 대시보드 (1)
<img src="https://github.com/user-attachments/assets/484be966-1c60-4f3b-8e96-32ae85933120" width="1200">

### MySQL 대시보드
<img src="https://github.com/user-attachments/assets/1059de1e-b59d-4646-9317-5ec1aca57cc9" width="1200">

### APLICATION 대시보드
<img src="https://github.com/user-attachments/assets/ee92b2f0-2577-49e7-a4fa-3fb2ff219e98" width="1200">

### WINDOW 대시보드
<img src="https://github.com/user-attachments/assets/0b544d36-d0e9-4903-9cee-9ffa5ec4cabc" width="1200">

### LOKI
![image](https://github.com/user-attachments/assets/fbda25da-a539-4c33-87dc-1887ce56b46e)

### TEMPO (1)
![image](https://github.com/user-attachments/assets/a3a192ec-44dd-47fa-affb-63854687386c)

### TEMPO (2)
![image](https://github.com/user-attachments/assets/3bad68fa-d34b-40f4-b186-7b972e53cce6)

### TEMPO (3)
![image](https://github.com/user-attachments/assets/dcd3d36e-f675-4108-939a-4760955bae7d)

### MINIO
![image](https://github.com/user-attachments/assets/2d21879a-397b-427b-b3a3-40dd5a4c16cf)

