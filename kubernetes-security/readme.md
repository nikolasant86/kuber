# Создал сервисный аккаунт 'monitoring'
# Сделал для него 'cluster role', 'cluster role binding'
# Доработал deployment.yaml чтобы поды открывались под сервисным аккаунтом, так же настроил корректное обращение к эндпоинту /metrics и сохрание в файл metrics.html 