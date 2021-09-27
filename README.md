Penjelasan Alur Program :

Ketika rumah terbakar maka jendela, kunci pintu, garasi dan fire sprinkler akan terbuka
sehingga orang yang berada di dalam bisa menyelamatkan diri

Rangkaian ini menggunakan alat Window, Door, Garage Door, Fire Sprinkler dan Fire Monitor
Fire Monitor berfungsi untuk mendeteksi jika ada Fire 

di bawah ini Script untuk Heating Element
function setup(){
	setDeviceProperty(getName(), 'IR', 900);
}
