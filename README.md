## Object Tracking using Kalman-Consensus Filter

This project demonstrates the effectiveness of using Kalman-consensus Filters on a network of heterogeneous sensors to track an object effectively. The algorithm leverages a consensus mechanism to improve the accuracy of even low-accuracy sensor nodes.

### Advantages
1. Decentralized in nature: There is no central node that carries out the tracking process
2. Reduced communication overhead: The Lack of a centralized node reduces the need for communicating the data back and forth to a central node
3. Distributed in nature: Every node in the network performs the tracking separately. This ensures continued functioning even when some sensor nodes fail
4. Consensus mechanism: The tracking of the sensor nodes is complemented by a consensus mechanism along with its neighbors. This enables us to reduce the need for high-accuracy sensors in the network and instead use several low-accuracy sensors paired with strategically placed high-accuracy sensors

More details can be found in my [blog](https://kalaiselvan-t.github.io/projects/2024-05-10-distributed-state-estimation/)
