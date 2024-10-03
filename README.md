# Praktikum 1: Membuat Project Flutter Baru

- Langkah 1
  Buka VS Code,
  <br> lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project
- Langkah 2
  <br>Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.
- Langkah 3
  <br>Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.
- Langkah 4
  Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.
  <br>
  <br>

# Pratikum 2: Menghubungkan Perangkat Android atau Emulator

- Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0
<br>
<br>

# Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum

- Langkah 1:<br>
  Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"
- Langkah 2:<br>
  Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.
- Langkah 3<br>
  Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

```
git init
```

- Langkah 4:<br>
  Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.
- Langkah 5:<br>
  Beri pesan commit "tambah gitignore" lalu klik Commit (✔)
- Langkah 6:<br>
  Lakukan push dengan klik bagian menu titik tiga > Push
- Langkah 7<br>
  Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"
- Langkah 8:<br>
  Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote
  <br>
  Setelah berhasil, tulis remote name dengan "origin"
- Langkah 9:<br>
  Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.
- Langkah 10:<br>
  Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.
- Langkah 11:<br>
  Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.
- Langkah 12:<br>
  Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.
  <br>
  <br>

# Praktikum 4

- Langkah 1: Text Widget<br>
  Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.
  ![alt text](https://github.com/ridlofebrio/flutter-fundamental-part1/blob/main/img/image.png)
- Langkah 2: Image Widget
  Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.
  Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.
  ![alt text](img\image2.png)

# Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino

- Langkah 1: Cupertino Button dan Loading Bar<br>
  Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
  ![alt text](img\image3.png)
- Langkah 2: Floating Action Button (FAB)<br>
  Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton. Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
  ![alt text](img\image4.png)

- Langkah 3: <br>
  Scaffold Widget
  Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.
  ![alt text](img\image5.png)

- Langkah 4: Dialog Widget <br>
  Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.
  ![alt text](img\image6.png)
  ![alt text](img\image7.png)

- Langkah 5: Input dan Selection Widget <br>
  Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.
  ![alt text](img\image8.png)

- Langkah 6: Date and Time Pickers <br>
  Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
  ![alt text](img\image9.png)


# Tugas

## First Hot ReloadAt 
the bottom of lib/main.dart, add something to the string in the first Text object, and save the file (with Ctrl+S or Cmd+S). For example:
![alt text](img\image10.png)
## Adding a button
When you save the change, the app updates again: A button appears and, when you click it, the Debug Console in VS Code shows a button pressed! message.
```dart
ElevatedButton(
            onPressed: () {
              print('button pressed!');
            },
            child: Text('Next'),
          ),
```
## A Flutter crash course in 5 minutes
As much fun as it is to watch the Debug Console, you want the button to do something more meaningful. Before getting to that, though, take a closer look at the code in lib/main.dart, to understand how it works.
```dart
void main() {
  runApp(MyApp());
}
```
At the very top of the file, you'll find the main() function. In its current form, it only tells Flutter to run the app defined in MyApp.
```dart

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return ChangeNotifierProvider(
      create: (context) => MyAppState(),
      child: MaterialApp(
        title: 'Namer App',
        theme: ThemeData(
          useMaterial3: true,
          colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepOrange),
        ),
        home: MyHomePage(),
      ),
    );
  }
}
```
The MyApp class extends StatelessWidget. Widgets are the elements from which you build every Flutter app. As you can see, even the app itself is a widget.
The code in MyApp sets up the whole app. It creates the app-wide state (more on this later), names the app, defines the visual theme, and sets the "home" widget—the starting point of your app.
```dart
class MyAppState extends ChangeNotifier {
  var current = WordPair.random();
}
```
![alt text](img\image11.png)

## Make the app prettier
he line responsible for showing the current word pair looks like this now: Text(appState.current.asLowerCase). To change it into something more complex, it's a good idea to extract this line into a separate widget. Having separate widgets for separate logical parts of your UI is an important way of managing complexity in Flutter.

Flutter provides a refactoring helper for extracting widgets but before you use it, make sure that the line being extracted only accesses what it needs. Right now, the line accesses appState, but really only needs to know what the current word pair is.

For that reason, rewrite the MyHomePage widget as follows
```dart
class MyHomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    var appState = context.watch<MyAppState>();  
    var pair = appState.current;                 // ← Add this.

    return Scaffold(
      body: Column(
        children: [
          Text('A random AWESOME idea:'),
          Text(pair.asLowerCase),                // ← Change to this.
          ElevatedButton(
            onPressed: () {
              appState.getNext();
            },
            child: Text('Next'),
          ),
        ],
      ),
    );
  }
}
```
In the Refactor menu, select Extract Widget. Assign a name, such as BigCard, and click Enter.

This automatically creates a new class, BigCard, at the end of the current file. The class looks something like the following:
```dart
class BigCard extends StatelessWidget {
  const BigCard({
    super.key,
    required this.pair,
  });

  final WordPair pair;

  @override
  Widget build(BuildContext context) {
    final theme = Theme.of(context);
    return Card(
       color: theme.colorScheme.primary,
      child: Padding(
        padding: const EdgeInsets.all(8.0),
        child: Text(pair.asLowerCase),
      ),
    );
  }
}
```
## Center the UI
Now that the random word pair is presented with enough visual flair, it's time to place it in the center of the app's window/screen.

First, remember that BigCard is part of a Column. By default, columns lump their children to the top, but we can easily override this. Go to MyHomePage's build() method, and make the following change:
```dart
    return Scaffold(
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            const Text('A random AWESOME idea:'),
            BigCard(pair: pair), 
            ElevatedButton(
              onPressed: () {
                appState.getNext(); 
              },
              child: const Text('Next'),
            ),
          ],
        ),
      ),
    );
```
![alt text](img\image12.png)

## Add functionality
Scroll to MyAppState and add the following code:
```dart
 var favorites = <WordPair>[];

  void toggleFavorite() {
    if (favorites.contains(current)) {
      favorites.remove(current);
    } else {
      favorites.add(current);
    }
    notifyListeners();
  }
```
## Add the button
With the "business logic" out of the way, it's time to work on the user interface again. Placing the ‘Like' button to the left of the ‘Next' button requires a Row. The Row widget is the horizontal equivalent of Column, which you saw earlier.
First, wrap the existing button in a Row. Go to MyHomePage's build() method, put your cursor on the ElevatedButton, call up the Refactor menu with Ctrl+. or Cmd+., and select Wrap with Row

```dart
 return Scaffold(
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            BigCard(pair: pair),
            SizedBox(height: 10),
            Row(
              mainAxisSize: MainAxisSize.min,   // ← Add this.
              children: [
                ElevatedButton(
                  onPressed: () {
                    appState.getNext();
                  },
                  child: Text('Next'),
                ),
              ],
            ),
          ],
        ),
      ),
    );
```
Next, add the Like button and connect it to toggleFavorite(). For a challenge, first try to do this by yourself, without looking at the code block below
```dart
ElevatedButton.icon(
  onPressed: () {
    appState.toggleFavorite();
    },
      icon: Icon(
          appState.favorites.contains(pair) ? Icons.favorite : Icons.favorite_border,
        ),
      label: Text('Like'),
  ),
```
![alt text](img\image13.png)

### Add navigation rail
To get to the meat of this step as soon as possible, split MyHomePage into 2 separate widgets.
Select all of MyHomePage, delete it, and replace with the following code:
```dart
class MyHomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Row(
        children: [
          SafeArea(
            child: NavigationRail(
              extended: false,
              destinations: [
                NavigationRailDestination(
                  icon: Icon(Icons.home),
                  label: Text('Home'),
                ),
                NavigationRailDestination(
                  icon: Icon(Icons.favorite),
                  label: Text('Favorites'),
                ),
              ],
              selectedIndex: 0,
              onDestinationSelected: (value) {
                print('selected: $value');
              },
            ),
          ),
          Expanded(
            child: Container(
              color: Theme.of(context).colorScheme.primaryContainer,
              child: GeneratorPage(),
            ),
          ),
        ],
      ),
    );
  }
}


class GeneratorPage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    var appState = context.watch<MyAppState>();
    var pair = appState.current;

    IconData icon;
    if (appState.favorites.contains(pair)) {
      icon = Icons.favorite;
    } else {
      icon = Icons.favorite_border;
    }

    return Center(
      child: Column(
        mainAxisAlignment: MainAxisAlignment.center,
        children: [
          BigCard(pair: pair),
          SizedBox(height: 10),
          Row(
            mainAxisSize: MainAxisSize.min,
            children: [
              ElevatedButton.icon(
                onPressed: () {
                  appState.toggleFavorite();
                },
                icon: Icon(icon),
                label: Text('Like'),
              ),
              SizedBox(width: 10),
              ElevatedButton(
                onPressed: () {
                  appState.getNext();
                },
                child: Text('Next'),
              ),
            ],
          ),
        ],
      ),
    );
  }
}
```
![alt text](img\image14.png)
### setState
The new stateful widget only needs to track one variable: selectedIndex. Make the following 3 changes to _MyHomePageState:
```dart
class _MyHomePageState extends State<MyHomePage> {
   var selectedIndex = 0;  // ← Add this property.
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Row(
        children: [
          SafeArea(
            child: NavigationRail(
              extended: false,
              destinations: [
                NavigationRailDestination(
                  icon: Icon(Icons.home),
                  label: Text('Home'),
                ),
                NavigationRailDestination(
                  icon: Icon(Icons.favorite),
                  label: Text('Favorites'),
                ),
              ],
              selectedIndex: selectedIndex, // ← Change to this.
              onDestinationSelected: (value) {
                // ↓ Replace print with this.
                setState(() {
                  selectedIndex = value;
                });
              },
            ),
          ),
          Expanded(
            child: Container(
              color: Theme.of(context).colorScheme.primaryContainer,
              child: GeneratorPage(),
            ),
          ),
        ],
      ),
    );
  }
}
```
### Use selectedIndex
Place the following code at the top of _MyHomePageState's build method, just before return Scaffold:
```dart
// ...

Widget page;
switch (selectedIndex) {
  case 0:
    page = GeneratorPage();
    break;
  case 1:
    page = Placeholder();
    break;
  default:
    throw UnimplementedError('no widget for $selectedIndex');
}

// ...
```
![alt text](img\image15.png)
### Responsiveness
Next, make the navigation rail responsive. That is to say, make it automatically show the labels (using extended: true) when there's enough room for them
![alt text](img\image16.png)

### Add a new page
Here's the new FavoritesPage class

```dart
class FavoritesPage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    var appState = context.watch<MyAppState>();

    if (appState.favorites.isEmpty) {
      return Center(
        child: Text('No favorites yet.'),
      );
    }

    return ListView(
      children: [
        Padding(
          padding: const EdgeInsets.all(20),
          child: Text('You have '
              '${appState.favorites.length} favorites:'),
        ),
        for (var pair in appState.favorites)
          ListTile(
            leading: Icon(Icons.favorite),
            title: Text(pair.asLowerCase),
          ),
      ],
    );
  }
}
```
![alt text](image.png)
