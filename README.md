# ViewExtensions
[![](https://jitpack.io/v/Ladgertha/ViewExtensions.svg)](https://jitpack.io/#Ladgertha/ViewExtensions)

The library with extensions for view.

## Пример использования:
```
view.hide() — replace view.visibility = View.GONE
view.show() — replace view.visibility = View.VISIBLE
view.invisible() — replace view.visibility = View.INVISIBLE
```

How to use:
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
