Soal No 1
$users = User::all(); lebih baik daripada $data = User::all(); 
karena memenuhi unsur coding standar variable dan collection.
Nama variable lebih mudah dikenali serta bersifat jamak.

Soal No 2
function storeCustomer() lebih baik daripada function save()
karena nama function jadi lebih mudah dikenali dan spesifik.

Soal No 3
Refactor dari kode berikut:

$total=0;
foreach($items as $i){
$total=$total+$i->price;
}

yaitu:

$totalPrice = 0;
foreach($items as $item){
    $totalPrice += $item->price;
}

