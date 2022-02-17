# Routing


You can make a route like this
```
Route::get('/url', function () {
    return view('view_name');
});

or

Route::view("url", 'view_name');
```

You can get a variable from view side 
```
Route::get('/url/{name}', function ($name) {
    echo $name;
    return view('blog');
});
```

Or you can send a variable from routing to view side
```
Route::get('/url', function () {
    $name = 'Ali Raza';
    return view('view_name', ['name'=>$name]);
});

```
and the view page look like this
```
<h1>This is a View page.</h1>
<h2>{{$name}}</h2>
```
