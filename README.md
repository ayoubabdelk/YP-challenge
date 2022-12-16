<h2 dir="ltr">
    The ADAS System
</h2>
<br/>
<p dir="ltr">
    An Advanced Driver Assistance System (ADAS) is a system that uses sensors,
    cameras, and other technology to assist a driver in operating a vehicle. In
    the context of lunar vehicles, an ADAS system would likely be used to help
    the driver navigate and operate the vehicle in the unique environment of
    the Moon. This could include features such as collision avoidance, terrain
    mapping, and other functions that would help the driver safely and
    efficiently operate the lunar vehicle.
</p>
<p dir="ltr">
    Some potential uses for an ADAS system in a lunar vehicle could include:
</p>
<ul>
    <li dir="ltr">
        <p dir="ltr">
            Terrain mapping: The Moon's surface is full of craters, hills, and
            other obstacles that can make it difficult to navigate. An ADAS
            system could use sensors and cameras to create a detailed map of
            the surrounding area, allowing the driver to see the best path to
            take and avoid any potential hazards.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            Collision avoidance: The low gravity of the Moon means that even a
            minor collision can have major consequences. An ADAS system could
            use sensors and cameras to detect potential collisions and
            automatically take evasive action to avoid them.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            Remote control: In some situations, it may be safer or more
            efficient for a human operator to control the lunar vehicle
            remotely rather than being on board. An ADAS system could allow the
            operator to remotely control the vehicle and its movements, giving
            them greater flexibility and control.
        </p>
    </li>
</ul>
<p dir="ltr">
    Some of the key components of an ADAS system might include:
</p>
<ul>
    <li dir="ltr">
        <p dir="ltr">
            Sensors: Sensors are used to detect the presence and position of
            other objects in the surrounding area. These sensors could include
            radar, lidar, ultrasonic sensors, or other types of sensors.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            Cameras: Cameras are used to provide visual information about the
            surrounding area. This could include visible-light cameras,
            infrared cameras, or other types of cameras.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            Software and algorithms: The ADAS system also includes software and
            algorithms that enable it to process the data from the sensors and
            cameras, calculate the vehicle's trajectory, and take appropriate
            action to avoid collisions or other hazards.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            Display: The ADAS system may include a display that shows the
            driver information about the surrounding area, such as a map of the
            terrain, the location of other vehicles, or other hazards.
        </p>
    </li>
</ul>
<br/>
<h3 dir="ltr">
    Terrain Mapping
</h3>
<p dir="ltr">
    Terrain mapping refers to the process of creating a detailed map of the
    surrounding area, typically using sensors and cameras to gather information
    about the terrain. In the context of a lunar vehicle, terrain mapping would
    involve using sensors and cameras to create a map of the Moon's surface,
    allowing the driver to see the best path to take and avoid any potential
    hazards.
</p>
<p dir="ltr">
    A terrain mapping system typically uses sensors such as lidar, radar, or
    cameras to gather information about the surrounding area. This information
    is then used to create a detailed map of the terrain, showing the location
    of obstacles, hills, valleys, and other features. The map is then displayed
    to the driver, either on a screen inside the vehicle or through a headset
    or other device.
</p>
<p dir="ltr">
    The use of terrain mapping technology is important in any vehicle that
    operates in challenging environments, such as off-road vehicles on Earth or
    lunar vehicles on the Moon. By providing the driver with a detailed map of
    the surrounding area, terrain mapping can help them navigate safely and
    efficiently, avoiding hazards and finding the best route to their
    destination
</p>
<p dir="ltr">
    terrain mapping is referred by the file Grid mapping
</p>
<p dir="ltr">
    <img
        src="https://lh5.googleusercontent.com/zuxFlkBNOOHgQcP01SeKoj6983oczHXIfaHWHTRfwvlmgJWtB00Fv8ktXp2LtYZSgaZ0QzyQYmqlcYen5IkzEtClfcvGD4F6zY1lqUuAORJVYbM9btx4YqAL8l6lgfaAVUVLSMKbR2GOygFtgATYU-jjIJjs77tnsif0SlB9cKnrcuO0IlVYA-HfCrg2Lg"
        width="473"
        height="232"
    />
</p>
<h3 dir="ltr">
    Publications
</h3>
<p dir="ltr">
    P. Fankhauser and M. Hutter, "A Universal Grid Map Library: Implementation
    and Use Case for Rough Terrain Navigation", in Robot Operating System (ROS)
– The Complete Reference (Volume 1), A. Koubaa (Ed.), Springer, 2016. (    <a href="http://www.researchgate.net/publication/284415855">PDF</a>)
</p>
<h3 dir="ltr">
    Packages Overview
</h3>
<p dir="ltr">
    This repository consists of following packages:
</p>
<ul>
    <li dir="ltr">
        <p dir="ltr">
            grid_map is the meta-package for the grid map library.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            grid_map_core implements the algorithms of the grid map library. It
            provides the GridMap class and several helper classes such as the
iterators. This package is implemented without            <a href="http://www.ros.org/">ROS</a> dependencies.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
grid_map_ros is the main package for            <a href="http://www.ros.org/">ROS</a> dependent projects using the
            grid map library. It provides the interfaces to convert grid maps
            from and to several <a href="http://www.ros.org/">ROS</a> message
            types.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            grid_map_demos contains several nodes for demonstration purposes.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
grid_map_filters builds on the            <a href="http://wiki.ros.org/filters">ROS Filters</a> package to
            process grid maps as a sequence of filters.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            grid_map_msgs holds the <a href="http://www.ros.org/">ROS</a>
            message and service definitions around the [grid_map_msg/GridMap]
            message type.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
grid_map_rviz_plugin is an            <a href="http://wiki.ros.org/rviz">RViz</a> plugin to visualize
            grid maps as 3d surface plots (height maps).
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            grid_map_sdf provides an algorithm to convert an elevation map into
            a 3D signed distance field.
        </p>
    </li>
    <li dir="ltr">
        <p dir="ltr">
            grid_map_visualization contains a node written to convert GridMap
            messages to other <a href="http://www.ros.org/">ROS</a> message
types for example for visualization in            <a href="http://wiki.ros.org/rviz">RViz</a>.
        </p>
    </li>
</ul>
<h3 dir="ltr">
    Collision Avoidance
</h3>
<p dir="ltr">
    The low gravity of the Moon means that even a minor collision can have
    major consequences. An ADAS system could use sensors and cameras to detect
    potential collisions and automatically take evasive action to avoid them.
</p>
<p dir="ltr">
    Collision avoidance refers to the use of technology to prevent collisions
    between vehicles, objects, or other hazards. In the context of a lunar
    vehicle, collision avoidance would involve using sensors and cameras to
    detect potential collisions and automatically take evasive action to avoid
    them. In a typical collision avoidance system, sensors such as radar or
    lidar are used to detect the presence and position of other objects in the
    vehicle's surroundings. The system then uses this information to calculate
    the trajectory of the vehicle and determine whether a collision is
    imminent. If a collision is detected, the system can automatically take
    evasive action, such as applying the brakes, steering the vehicle away from
    the hazard, or both. The use of collision avoidance technology is important
    in any vehicle, but it is particularly important in a lunar vehicle because
    the low gravity of the Moon means that even a minor collision can have
    major consequences. By automatically detecting and avoiding potential
    collisions, an ADAS system can help prevent accidents and keep the vehicle
    and its occupants safe.
</p>
<br/>
<p dir="ltr">
    rocks and other debris: The Moon's surface is full of rocks and other
    debris that could cause damage if the vehicle collides with them. A
    collision avoidance system would need to detect and avoid these hazards to
    keep the vehicle safe. Craters: The Moon's surface is also full of craters,
    some of which could be deep enough to cause significant damage to a vehicle
    if it were to fall into one. A collision avoidance system would need to
    detect and avoid these craters to prevent accidents. Hills and valleys: The
    Moon's surface is uneven, with hills, valleys, and other features that
    could make it difficult to navigate. A collision avoidance system would
    need to detect and avoid these hazards to help the driver find the best
    path to take. Overall, a collision avoidance system in a lunar vehicle
    would need to be able to detect and avoid a wide range of hazards on the
    Moon's surface, including other vehicles, rocks, craters, and other
    obstacles. By doing so, it can help prevent accidents and keep the vehicle
    and its occupants safe
</p>
<p dir="ltr">
    collision avoidance is referred by dynamic obstacle avoidance
</p>
<br/>
<h2 dir="ltr">
    This package contains a dynamic obstacle avoidance algorithm for concave
    and convex obstacles as developped in [1] and [2]. The Code is still in
    alpha version.
</h2>
<h3 dir="ltr">
    Description
</h3>
<p dir="ltr">
    The algorithms allows to avoid dynamic, star-shaped obstacles. It requires
    anlytical description of the environment. It allows to navigate within
    moving, expanding and static obstacles.
</p>
<br/>
<br/>
<p dir="ltr">
    References
</p>
<p dir="ltr">
    [1] Huber, Lukas, Aude Billard, and Jean-Jacques E. Slotine. "Avoidance of
    Convex and Concave Obstacles with Convergence ensured through Contraction."
    IEEE Robotics and Automation Letters (2019).
</p>
<p dir="ltr">
    [2] Huber, Lukas, and Slotine Aude Billard. "Avoiding Dense and Dynamic
    Obstacles in Enclosed Spaces: Application to Moving in a Simulated Crowd."
    arXiv preprint arXiv:2105.11743 (2021).
</p>
<p dir="ltr">
    Contact: [Lukas Huber] (
    <a href="https://people.epfl.ch/lukas.huber?lang=en">
        https://people.epfl.ch/lukas.huber?lang=en
    </a>
    ) (lukas.huber AT epfl dot ch)
</p>
<p dir="ltr">
    Acknowledgments This work was funded in part by the EU project Crowdbots.
</p>
<p dir="ltr">
    (c) hubernikus
</p>
<h3 dir="ltr">
    Trajectory Calculation 
</h3>
<p dir="ltr">
    These algorithms are used to calculate the vehicle's trajectory based on
    the data from the sensors and cameras. This could include algorithms that
    use kinematics, physics, or other principles to predict the vehicle's
    future position and velocity.
</p>
<p dir="ltr">
    trajectory calculation is referred by Fast and Safe Trajectory Planner
</p>
<h3 dir="ltr">
    FASTER: Fast and Safe Trajectory Planner for Navigation in Unknown
    Environments
</h3>
<h3 dir="ltr">
    Accepted for publication in the IEEE Transactions on Robotics (T-RO)
</h3>
<h3 dir="ltr">
    Finalist to the Best Paper Award on Safety, Security, and Rescue Robotics
    (IROS 2019)
</h3>
<p dir="ltr">
    <img
        src="https://lh3.googleusercontent.com/MfGsx7CsB3_HyZ1TIkFoC4DF4-RU9kLP_kAc5KHFamZy5-WcatmlPEs5-_RibKL0DwjGfwYTRj6S4LHg_xxxCN_juWvsdzVAFj2scSnIscuPzjEgspQ7I-UEV1uytOyAdkujU31kFAPZa4NpT5GKq5jOyVvARoJq8gYprfl1QQZXLjj-77GYSrDKjbK21w"
        width="282"
        height="157"
    />
    <img
        src="https://lh5.googleusercontent.com/qHzJ2Ed6ySyVwf_RrFSJeV5W6uD0FW_HPHCNKagGI7n9lZgHeVfu4IqLUp4AHedcRcNp_OISUq2OvhwIveZHUqyKmRDmgpwiphR4oA-h0mxBVhnkCrR27fuNhqhJUOE8h4vXmqLqKcXOiuI-5yg4I0eGyIKSvqSiBhF0mumHlCQmyg4I_sIhzddXCRvtOg"
        width="280"
        height="157"
    />
</p>
<br/>
<p dir="ltr">
    <img
        src="https://lh5.googleusercontent.com/ZvVzeLucQwq2TLXa-sY3qEGv2H0HoQBoLfaGGUPEPoVDdrG-i89Qp3izuR_tCflpKLHzFSkKfrLU_03ZY4UuVyi1Fr1nt_laxgXmacwA_gjpWhUWFxE9DXGAqk4znUuDcREHUgGfgN3Fd6bmGI4Prqwibjp5ZecCCp5bhvtVa7mdax4UECLFtl3tijLv6g"
        width="268"
        height="152"
    />
    <img
        src="https://lh4.googleusercontent.com/iRmzRcAyJuTYKZDS6204t2aE1dJnJFD2F9tp4yY98_k4vSYdhXjbIrEUBOoE8trORexgBIPjTCfYWvdxsFAIhylD5rTiTHM8vw9KQ4WHM1S6YFlEGJ7T8eXT8AbSWLRqsYf2dj8dQ2XpUjPpSC_UAzzbi7WiYeRSJ-xFpx2p43wdLda-hFiB57ldQUGkpA"
        width="274"
        height="154"
    />
</p>
<div>
    <br/>
</div>
