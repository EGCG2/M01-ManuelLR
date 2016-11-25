# M01-ManuelLR

- Crear proyeco maven: 
```bash
mvn -B archetype:generate \
  -DarchetypeGroupId=org.apache.maven.archetypes \
  -DgroupId=com.mycompany.app \
  -DartifactId=my-app
```

- Los scope indican donde hacen falta las librerías para que solo se descarguen en el entorno que es necesario. Por ejemplo, si pone test solo se descargará cuando se vayan a pasar los test.
