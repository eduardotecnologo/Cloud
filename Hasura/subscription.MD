subscription MySubscription {
  user(where: {
    email: {
      _ilike: "@gmail.com"
    }
  }) {
    id
    name
    email
  }
}

