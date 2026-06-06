class Book {
    private String title;
    private String author;
    private boolean isAvailable;

    // Constructor
    Book(String title, String author, boolean isAvailable) {
        this.title = title;
        this.author = author;
        this.isAvailable = isAvailable;
    }

    void display() {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.println("Available: " + isAvailable);
    }

    public static void main(String[] args) {
        Book b1 = new Book("Java Programming", "James Gosling", true);
        b1.display();
    }
}
