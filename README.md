# ViewExtensions
[![](https://jitpack.io/v/Ladgertha/ViewExtensions.svg)](https://jitpack.io/#Ladgertha/ViewExtensions)

Библиотека с расширениями для view.

## Пример использования:
```
view.hide() — заменяет view.visibility = View.GONE
view.show() — заменяет view.visibility = View.VISIBLE
view.invisible() — заменяет view.visibility = View.INVISIBLE
```

Подключение:
- Gradle:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
```
implementation 'com.github.Ladgertha:ViewExtensions:v1.0.1'
```

- Maven:
```
<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
</repositories>
```
```
<dependency>
	  <groupId>com.github.Ladgertha</groupId>
	  <artifactId>ViewExtensions</artifactId>
	  <version>v1.0.1</version>
</dependency>
  ```
