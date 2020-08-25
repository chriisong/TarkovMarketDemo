# TarkovMarket
**TarkovMarket** is a simple market information app for Battlestate Game’s Escape from Tarkov. It retrieves data using a 3rd party API service and displays it appropriately on UITableView and UICollectionView using the latest Diffable Data Source technology for responsive, reactive, and powerful performance. The app uses Core Data for persistence to enable users to favourite their desired items for quick access.

#### Technology: Core Data, CloudKit, Diffable Data Source, REST API, UIRefreshControl, ResultTypes
#### 3rd Party Libraries: None
#### TestFlight Public Link: https://testflight.apple.com/join/PQc27sZx

## Screen Recordings

### UIRefreshControl to update prices 
![Alt Text](Gifs/UIRefreshControl.gif)

### Empty State View and updating Core Data Entity to toggle `isFavourited` property
![Alt Text](Gifs/EmptyState.gif)

### Using Diffable Data Source to filter search controller results
![Alt Text](Gifs/Diffing.gif)

### Sorting Core Data objects using NSPredicate
![Alt Text](Gifs/Sorting.gif)
