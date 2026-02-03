Get-Content README.md

# Если пустой или неправильный, заполните заново
"# Мой тестовый проект" | Out-File README.md -Encoding UTF8
"Это учебный проект создан для Димы в рамках работы с GitHub." | Add-Content README.md -Encoding UTF8