
# YouTube Portfolio


<dl>
<dt>Course Name</dt>
<dd>Algorithmic Problem Solving</dd>
<dt>Course Code</dt>
<dd>23ECSE309</dd>
<dt>Faculty </dt>
<dd>Prakash Hegade</dd>
<dt>University</dt>
<dd>KLE Technological University, Hubballi-31</dd>
</dl>

* * *

> A step towards YouTube Functionalities in terms of APS
>
>Abhijna

#### Note:
Functionalities aimed to cover (click on the functionality to discover):
<!--1. [Order of Video Playing](./order_of_video_playing.md)
2. [Search for Videos](./search_for_videos.md)
3. [Video Recommendations](./video_recommendations.md)
4. [Video Playback Control](./video_playback_control.md)
5. [Video Upload and Processing](./video_upload_and_processing.md)
6. [User Engagement Analysis](./user_engagement_analysis.md)
-->


## 1. Video Playback
### Concepts Used:
- **Heap Design (Flat and Hierarchy, Transform and Conquer)**: Manages video buffering by prioritizing video segments for smooth playback. The heap structure ensures that the most important segments (e.g., those closest to the current playback position) are loaded first.
- **Sliding Window**: Handles continuous streaming and buffering by maintaining a fixed-size window over the video timeline. As the user watches the video, the window slides forward, fetching and buffering new segments to prevent interruptions.

## 2. Search
### Concepts Used:
- **Trie and Radix Tree**: Provides efficient indexing and fast lookup for video titles, descriptions, and tags. This data structure supports quick searches and autocomplete functionality by storing each character of the search terms in nodes.
- **A* with priority queue**: Ranks search results based on relevance. This algorithm considers multiple factors such as title matches, view count, likes, and user engagement to deliver the most pertinent results to the user.

## 3. Channel Subscription
### Concepts Used:
- **Union-Find Basic**: Efficiently manages the relationships between users and their subscribed channels. This structure helps quickly determine if a user is subscribed to a channel and handles subscription/unsubscription operations.
- **BST (with basic function implementations insert, inorder, delete)**: Stores and manages subscription data in a binary search tree, allowing efficient insertion, deletion, and in-order traversal to quickly access subscribed channels.

## 4. Comments
### Concepts Used:
- **Segment Trees**: Manages and retrieves comments based on their timestamps. Segment trees allow efficient querying of comments within a specific time range, which is useful for displaying recent comments first.
- **Trie and Radix Tree**: Facilitates efficient storage and retrieval of comments based on keywords or phrases. This structure supports fast lookups for comments containing specific terms.

## 5. Like/Dislike
### Concepts Used:
- **Fenwick / BIT**: Efficiently updates and queries the count of likes and dislikes for videos. Binary Indexed Trees allow quick updates and cumulative frequency queries, which is essential for real-time like/dislike counts.
- **Segment Trees**: Handles range queries and updates on like/dislike data. Segment trees provide a way to quickly retrieve the total number of likes/dislikes within a range of videos.

## 6. Playlists
### Concepts Used:
- **Dynamic Programming (Ways to Reach a Number)**: Optimizes playlist duration based on user preferences and constraints. This approach finds the optimal combination of videos that fits within the desired total duration while maximizing user satisfaction.
- **Heap Implementation**: Manages and prioritizes videos within a playlist. Heaps ensure that the most preferred or recently added videos are easily accessible and can be played first.

## 7. Share
### Concepts Used:
- **Copy on Write**: Efficiently handles shared video links and metadata without duplicating data. Changes to shared content are only made when necessary, reducing resource usage.
- **Lazy Propagation**: Defers updates and propagation of shared video data until necessary. This approach optimizes performance by minimizing unnecessary operations.

## 8. Upload
### Concepts Used:
- **Union-Find root method**: Manages video chunks during the upload process. Each chunk is represented as a node, and union operations merge chunks into the complete video file.
- **Fenwick / BIT**: Tracks upload progress efficiently. Each node represents a segment of the video file, and progress updates are propagated through the tree.

## 9. Notifications
### Concepts Used:
- **A* with priority queue**: Manages and prioritizes notification delivery. Notifications are ranked based on factors such as user engagement history and channel popularity to ensure the most relevant notifications are delivered first.
- **Trie and Radix Tree**: Stores and retrieves user notification preferences. This structure supports efficient lookup and customization of notification settings.

## 10. Live Streaming
### Concepts Used:
- **Heap (intuition and design)**: Prioritizes incoming data packets during live streaming. Heaps ensure that high-priority packets, such as keyframes, are processed first to maintain smooth playback.
- **Sliding Window**: Manages real-time buffering and playback by maintaining a fixed-size window over the stream timeline. This approach adapts to network conditions and viewer preferences to provide a seamless streaming experience.






* * *
