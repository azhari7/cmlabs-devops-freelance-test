Penjelasan Terkait File dalam Folder Project

Di dalam folder project tersebut terdapat 2 file limit-node.yml sebagai configurasi agar tiap node hanya maximal deploy 3 pod
dan deployment.yml untuk deploy 6 pod replika dan limit memory 128 MB. asumsi misal ada dua node terkonfigurasi menggunakan limit-node.yml
maka akan ada 3 pod per node nya 
