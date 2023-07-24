# laravel-Paginator

<h1>1º passo<h1>
<p>Procure pelo seguinte arquivo AppServiceProvider.php localizado no seguinte caminho <br> "<strong>seuprojeto\app\Providers\AppServiceProvider.php</strong>"</p>

<h1>2º passo<h1>
<span>Dentro deste arquivo embaixo do trecho: <strong style="color:#ffffff;">"use Illuminate\Support\ServiceProvider";</strong><br> copie o seguinte trecho "<strong>use Illuminate\Pagination\Paginator;
</strong>"<br> deverá ficar assim "<strong>use Illuminate\Support\ServiceProvider;<br>
use Illuminate\Pagination\Paginator;</strong>"</span>

<h1>3º passo<h1>

Depois localize o seguinte trecho: "<strong> public function boot()<br>
    {<br>
    //
    }<br></strong>"
    E adicione este trecho no lugar das barras de comentários "<strong>Paginator::useBootstrap(); </strong><br>"
    E ficara assim:<br>
    "<strong> public function boot()<br>
    {<br>
    //
    }<br></strong>"

<h1>4º passo<h1>

Agora é só testar, você também pode baixar o arquivo já pronto e intalar no local indicado "seuprojeto\app\Providers\" copie e substitua o arquivo.
