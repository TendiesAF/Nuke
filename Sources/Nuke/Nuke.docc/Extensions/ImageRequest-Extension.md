# ``Nuke/ImageRequest``

## Image Processing

Set ``ImageRequest/processors`` to apply one of the built-in processors that can be found in ``ImageProcessors`` namespace or a custom one.

```swift
request.processors = [.resize(size: imageView.bounds.size)]
```

> Tip: See <doc:image-processing> for more information on image processing.

## Topics

### Initializers

- ``init(url:processors:priority:options:userInfo:)``
- ``init(urlRequest:processors:priority:options:userInfo:)``
- ``init(id:data:processors:priority:options:userInfo:)``
- ``init(id:dataPublisher:processors:priority:options:userInfo:)``

### Options

- ``processors``
- ``priority-swift.property``
- ``options-swift.property``
- ``userInfo``

### Nested Types

- ``Priority-swift.enum``
- ``Options-swift.struct``
- ``UserInfoKey``
- ``ThumbnailOptions``