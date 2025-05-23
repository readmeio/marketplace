# Postman Run Button Component

Adds a Postman Run Button to your documentation, allowing users to fork a Postman collection.

### Usage

```mdx
<PostmanRunButton 
  collectionId="123456-abcd-efgh-ijkl" 
  collectionUrl="entityId=123456-abcd-efgh-ijkl&entityType=collection&workspaceId=abcdef-1234-5678"
/>
```

### How to Find Your Collection ID and URL

1. Open your collection in Postman
2. Click "Share" button at the top right of your collection
3. Go to the "Via API" tab
4. You'll find your Collection ID in the URL or in the API response
5. The Collection URL contains parameters after the main URL (starting with "entityId=")

### Props

- `collectionId` (required): The ID of your Postman collection (e.g., "123456-abcd-efgh-ijkl")
- `collectionUrl` (required): The URL parameters for your collection, typically in this format: 
  `entityId=YOUR_COLLECTION_ID&entityType=collection&workspaceId=YOUR_WORKSPACE_ID`