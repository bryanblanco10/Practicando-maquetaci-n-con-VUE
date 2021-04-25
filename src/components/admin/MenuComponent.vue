<template>
    <!-- SideBar -->
    <section class="cover sideBar">
        <div class=" sideBar-ct">
            <!-- sideBar-title -->
            <div class="text-center text-uppercase sideBar-title">
                pidelo
            </div>
            <!-- SideBar - User info -->
            <div class="sideBar-UserInfo">
                <figure class="">
                    <img src="../../assets/img/avatar.png" alt="User">
                    <figcaption class="text-center">Bryan Blanco</figcaption>
                </figure>
                <ul class="text-center">
                    <li>
                        <a href="#">
                            <font-awesome-icon :icon="['fas', 'cog']" />
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <font-awesome-icon :icon="['fas', 'power-off']" />
                        </a>
                    </li>
                </ul>
            </div>
            <!-- SideBar - Menu -->

            <ul class="list-unstyled full-box sideBar-menu">
                <li>
                    <a href="#">
                         <font-awesome-icon :icon="['fas', 'home']"/> Dashboard
                    </a>
                </li>
                <li>
                    <a href="#!">
                        <font-awesome-icon :icon="['fas', 'suitcase']"/> Administraciòn <font-awesome-icon :icon="['fas', 'angle-down']" class="angledown"/>
                    </a>
                    <ul class="list-unstyled full-box">
                        <li>
                            <a href="#">
                                <font-awesome-icon :icon="['fas', 'user']"/> Usuario
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <font-awesome-icon :icon="['fas', 'user']"/> Usuario
                            </a>
                        </li>
                    </ul>
                </li>
            </ul>
        </div>
    </section>
</template>
<script>
export default{
    name: 'MenuComponent'
};
</script>