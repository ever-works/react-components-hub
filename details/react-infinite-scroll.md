## Overview

React Infinite Scroll is a component that automatically loads more content as the user scrolls near the bottom of the page, providing a smooth infinite scrolling experience.

## Key Features

- **Automatic Loading**: Load on scroll
- **Threshold Control**: Custom scroll distance
- **Loading Indicator**: Show loading state
- **End Detection**: Detect end of list
- **Pull to Refresh**: Refresh support
- **Reverse Direction**: Load upwards
- **Scroll Container**: Custom scroll parent
- **TypeScript**: Type support

## Features

- Detect scroll near bottom
- Auto-load content
- Loading state display
- End-of-list indicator
- Pull-to-refresh
- Loader component
- End message
- Reverse scrolling
- Custom scroll parent
- Scroll position save

## Props

- dataLength: Current data length
- next: Callback to load more
- hasMore: More content available
- isLoading: Loading state
- loader: Loading component
- endMessage: End-of-list message
- scrollThreshold: Scroll distance
- scrollableTarget: Scroll container
- pullToRefresh: Enable refresh
- refreshFunction: Refresh callback

## Usage

```jsx
<InfiniteScroll
  dataLength={items.length}
  next={loadMore}
  hasMore={hasMore}
  loader={<Loader />}
>
  {items.map(item => ...)}
</InfiniteScroll>
```

## Use Cases

- Social Media Feed
- Search Results
- Product Lists
- News Feed
- Comments List
- Message History
- Photo Gallery
- Data Tables

## Performance

- Efficient rendering
- Throttled scroll
- Memory management

## Pricing

Free and open-source under the MIT license.