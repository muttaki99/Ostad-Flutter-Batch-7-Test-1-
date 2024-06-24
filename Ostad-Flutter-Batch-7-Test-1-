class Media {
  // Method to play media
  void play() {
    print("Playing media...");
  }
}

// Derived class Song inheriting from Media
class Song extends Media {
  String artist;

  // Constructor to initialize artist
  Song(this.artist);

  // Overriding the play() method
  @override
  void play() {
    print("Playing song by $artist...");
  }
}

void main() {
  // Create an instance of Media
  Media media = Media();
  media.play();

  // Create an instance of Song
  Song song = Song("muttaki");
  song.play();
}
