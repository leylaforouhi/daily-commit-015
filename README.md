def capitalize_words(text):
    return " ".join(word.capitalize() for word in text.split())

if __name__ == "__main__":
    sample = "github daily commit"
    print(f"Capitalized: {capitalize_words(sample)}")
