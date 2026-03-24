# SaaSHub

[SaaSHub](https://www.saashub.com/) is a software alternatives and SaaS discovery platform that helps users find and compare software products, discover alternatives to existing tools, and explore new SaaS offerings. The platform aggregates community-driven reviews, ratings, and comparisons across thousands of software products and categories.

## API

SaaSHub provides a public API ([https://www.saashub.com/site/api](https://www.saashub.com/site/api)) that allows developers to programmatically query the platform's software database. The API is in beta and follows the [JSON:API](https://jsonapi.org/) specification.

### Endpoints

- **Product endpoint** — Returns the first product matching a given query string.
  ```
  https://www.saashub.com/api/product/{query}?api_key={your_api_key}
  ```

- **Alternatives endpoint** — Returns the first matching product along with its top 10 relevant alternatives.
  ```
  https://www.saashub.com/api/alternatives/{query}?api_key={your_api_key}
  ```

### Authentication

API access requires an API key. All SaaSHub registered users can find their API key in their profile at [https://www.saashub.com/profile/api_key](https://www.saashub.com/profile/api_key).

### Requirements

Users of the SaaSHub API are required to disclose on their website that they are using SaaSHub's API.

## Links

- [Website](https://www.saashub.com/)
- [API Documentation](https://www.saashub.com/site/api)
- [FAQ](https://www.saashub.com/faq)
- [Newsletter](https://www.saashub.com/newsletter)
- [Privacy Policy](https://www.saashub.com/site/privacy)
- [Sign Up](https://www.saashub.com/users/sign_up)
- [X (Twitter)](https://twitter.com/saashubcom)
