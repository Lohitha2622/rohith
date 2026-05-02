from selenium import webdriver
from selenium.webdriver.edge.service import Service
from selenium.webdriver.common.by import By
import time

# Correct path to msedgedriver.exe
service = Service("C:\\Users\\K Joshna Rani\\Downloads\\edgedriver_win64\\msedgedriver.exe")

driver = webdriver.Edge(service=service)

# Open Google
driver.get("https://www.google.com")
time.sleep(2)

# Find search box
search_box = driver.find_element(By.NAME, "q")
print("Search box element found:", search_box)

driver.quit()


from selenium import webdriver
from selenium.webdriver.edge.service import Service
import time

service = Service("C:\\Users\\Pranathi\\Downloads\\edgedriver_win64\\msedgedriver.exe")

driver = webdriver.Edge(service=service)
driver.get("https://www.google.com")
time.sleep(20)

driver.quit()


from selenium import webdriver
from selenium.webdriver.edge.service import Service
import time

service = Service("C:\\Users\\Pranathi\\Downloads\\edgedriver_win64\\msedgedriver.exe")

driver = webdriver.Edge(service=service)
driver.get("https://www.facebook.com")
time.sleep(20)

driver.quit()
