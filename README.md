## This is a great project

```js
public class CartControllerTest
    {
        private readonly Mock<ICatalogService> _catalogServiceMock;
        private readonly Mock<IBasketService> _basketServiceMock;
        private readonly Mock<IIdentityParser<ApplicationUser>> _identityParserMock;
        private readonly Mock<HttpContext> _contextMock;

        public CartControllerTest()
        {
            _catalogServiceMock = new Mock<ICatalogService>();
            _basketServiceMock = new Mock<IBasketService>();
            _identityParserMock = new Mock<IIdentityParser<ApplicationUser>>();
            _contextMock = new Mock<HttpContext>();
        }
    }
```

### TODO: code implementation
