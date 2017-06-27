Laravel Comandos Random
============

1. *Eliminar un table*

```php
Schema::drop('posts')
```


2. *Conexión exitosa con la DB*

```php
DB::connection()->getPdo()
```

3. *Creamos tabla*

```php
php artisan make:migration create_post_table --create=posts

            $table->string('title');
            $table->text('description');
            $table->string('url');

```

4. *Listar todas las tablas con Artisan Tinker*

```php
DB::select('select * from sqlite_master where type="table"')
```

5. *Si borras un archivo y quieres limpiar el buffer*

```php
composer dump-autoload
```
