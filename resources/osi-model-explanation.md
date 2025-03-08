# The OSI Model: How Computers Talk to Each Other

## What is the OSI Model?

The OSI (Open Systems Interconnection) model is like a map that shows how computers and networks communicate. Think of it as a seven-layer cake where each layer has a special job to help information travel from one computer to another!

## The Seven Layers

![OSI Model Layers](resources/osi-model-diagram.png)

### Layer 1: Physical Layer 
**Color in Site-Savvy: Brown Square ■**

This is the bottom layer that deals with the actual hardware - the cables, wires, and physical parts of the network. It's like the roads that information travels on.

**Examples:** Ethernet cables, fiber optic cables, wireless signals, network adapters

### Layer 2: Data Link Layer
**Color in Site-Savvy: Orange Triangle ▲**

This layer creates a reliable link between two directly connected nodes and handles the basic error checking. It's like the traffic rules that help data packets travel safely.

**Examples:** Switches, MAC addresses, network interface cards

### Layer 3: Network Layer
**Color in Site-Savvy: Orange Triangle ▲**

The network layer figures out the best path for data to travel across multiple networks to reach its destination. It's like a GPS system that finds the best route for your data.

**Examples:** Routers, IP addresses, routing protocols

### Layer 4: Transport Layer
**Color in Site-Savvy: Yellow Diamond ◆**

This layer ensures data is delivered completely and in the right order. It's like a mail carrier making sure your package arrives in one piece.

**Examples:** TCP, UDP, ports, load balancers

### Layer 5: Session Layer
**Color in Site-Savvy: Green Hexagon ⬢**

The session layer sets up, manages, and ends connections between applications. It's like starting and ending a phone call.

**Examples:** Session establishment, session authentication, message queuing

### Layer 6: Presentation Layer
**Color in Site-Savvy: Blue Circle ●**

This layer translates data between the application and the network format. It's like a translator who helps two people who speak different languages understand each other.

**Examples:** Data encryption, data compression, character encoding

### Layer 7: Application Layer
**Color in Site-Savvy: Multiple Colors**

The top layer is where network applications like web browsers and email clients operate. It's what users actually see and interact with.

**Examples:** Web browsers, email, DNS, file transfers

## How It Works Together

Imagine sending a message to a friend over the internet:

1. **Application Layer (7)**: You type a message in your chat app
2. **Presentation Layer (6)**: Your message gets formatted and possibly encrypted
3. **Session Layer (5)**: A connection is established with your friend's device
4. **Transport Layer (4)**: Your message is broken into packets for reliable delivery
5. **Network Layer (3)**: The best route is chosen for your packets
6. **Data Link Layer (2)**: Your data is prepared to travel over the physical network
7. **Physical Layer (1)**: Electrical signals carry your message through cables or wireless signals

Then, the process happens in reverse when your friend receives the message!

## Why It Matters in Site-Savvy

In our game, each color and shape represents different layers of the OSI model. When you match cards, you're actually modeling how real computer systems work together. The more you play, the more you'll understand how computer networks function!

- **Lower Layers (1-3)**: Physical hardware, connections, and routing (represented by Brown and Orange)
- **Middle Layers (4-5)**: Data transport and sessions (represented by Yellow and Green)
- **Upper Layers (6-7)**: User interfaces and applications (represented by Blue, Purple, and Pink)

Understanding these connections helps you both win the game and learn real technology concepts!

## The "Unofficial" Layer 8: The Human Layer
**Color in Site-Savvy: People of all colors!**

While not part of the official OSI model, technology professionals often talk about "Layer 8" as the human layer. After all, technology exists to serve people!

This layer represents the users, their needs, emotions, and experiences. The most perfectly designed network is useless if it doesn't help real people solve real problems.

**Examples:** User experience, digital literacy, emotional responses, accessibility needs

### Understanding the Human Layer

When building or maintaining technology systems, consider:
- Who will use this system?
- What are their needs and goals?
- What emotions might they experience when using it?
- What obstacles might they face?

![Emotional Technology Experience Map](resources/emotional-tech-map.png)

The most successful IT professionals don't just understand packets and protocols—they understand people. In Site-Savvy, when you collaborate with other players or consider the effects of your moves on others, you're practicing Layer 8 thinking!

Remember: Technology should bring people together, not create barriers between them.