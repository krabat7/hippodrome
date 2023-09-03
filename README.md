Дана программа – иммитация ипподрома.

Твоя задача – добавить тестирование и логирование.
Список необходимых тестов:
В следующем списке каждый пункт нужно реализовать как отдельный тестовый метод. Придумывая имена тестовым методам, старайся быть лаконичным, но в то же время чтобы можно было примерно понять, что именно в них тестируется.

Логи должны писаться в файл hippodrome.log, который должен располагаться в корне проекта в папке logs. Каждый день файл должен переименовываться по шаблону в hippodrome.2021-12-31.log и вместо него должен создаваться новый hippodrome.log. Для этого используй аппендер RollingFile. При этом файлы старше 7 дней, должны удаляться. Для этого можешь использовать конструкцию вида: