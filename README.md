# Unity-Addressables

🌟 Hello everyone! Today, I'm thrilled to share a peek into my latest venture—delving into Unity Addressables.

🎮 Addressables, the innovative feature by Unity3D, revolutionizes asset loading. It enables fetching assets through simple addresses, whether stored locally or remotely. By loading necessary assets at runtime, Addressables drastically reduce build times, installation sizes, and Unity Editor play times. Moreover, they play a crucial role in delivering content for deployed games and applications.

🏞️ Let's explore some key scenes within this project:

1️⃣ Scenes/BasicReference: Witness the simplest example showcasing the use of references to spawn and destroy game objects. Each object instantiation through AssetReference increments the reference count. Additionally, objects come with a script that triggers self-destruction after a specified duration, effectively destroying the object and decrementing the reference count. Any lingering instances upon scene closure are automatically released, ensuring a tidy decrement of the reference count even if their self-destruct script was disabled.

2️⃣ Scenes/ListOfReferences: Dive deeper into the utilization of references within a list. Here, the AssetReference cleverly retains a member called '.Asset'. Notably, it's crucial to note that relying solely on the on-complete callback to save loaded assets may not preserve the load order. This feature proves invaluable as references autonomously keep track of their loaded assets.

🚀 Addressables in Unity open up a world of possibilities, optimizing asset management and offering streamlined methods for asset loading, effectively enhancing the efficiency and performance of game development.

🔗 Interested in exploring more about Unity Addressables and their incredible potential? Subscribe and hit the notification bell to stay tuned for further insights, tutorials, and deep dives into the world of game development!

#Unity #GameDevelopment #EndlessRunner #2DGame #AI #EnemyMovement #Animation #IndieGameDev #GameDesign #Gamedev #UnityTutorial #GameDevTutorial #GameDevCommunity #IndieGame #IndieGameDevelopment #GameArt #IndieDev #GameDeveloper #GameProgramming #GameDesigning
