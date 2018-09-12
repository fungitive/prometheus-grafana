# kubernetes监控prometheus+grafana

    kubectl apply -f .
访问grafana

    http://localhost:30006
默认账号/密码：admin/admin
添加数据源：prometheus
grafan监控kubernetes主要使用三个模板，可以直接引入

    cluster：  https://grafana.com/dashboards/162
    pods：  https://grafana.com/dashboards/747
    deploy：   https://grafana.com/dashboards/741

参考：

    https://github.com/prometheus/prometheus/tree/master/documentation/examples
