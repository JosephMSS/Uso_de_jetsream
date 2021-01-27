## Para la creacion de projectos con JetStream podemos ingresar el siguiente comanto a la consola 
`laravel new j-liveware-8 --jet`
## Creacion de componentes liveware
` php artisan make:livewire CourseList`
## Uso de componentes livewire
 Para hacer uso de estos componentes unicamente debemos emplear el siguiente formato
`<livewire:[nombre del componete alamcenado en la carpeta  de vistas]>`
 ademas existe un controlador el cual se encarga de manejar cada uno de los componetes.
 ## COmponentes
De esta manera enviamos parametros a los componentes , de esta manera el componente livewire emplea el componente blade [example](resources\views\livewire\course-list.blade.php)

 `php artisan make:component course-card` este comando generara un nuevo compnente el cual va a estar almacenado en una nueva carpeta llamada components, 