<template>
  <nav>
    <v-app-bar color="red" dark app>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title class="text-uppercase">
        <span class="font-weight-light">Akzere</span>
        <span> Big Byte</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text>
        <span>Exit</span>
        <v-icon right>exit_to_app</v-icon>
      </v-btn>
    </v-app-bar>
  </nav>
</template>

<script>
export default {
  data: () => ({
    drawer: true,
    links: [
      { icon: "dashboard", text: "dashboard", route: "/" },
      { icon: "folder", text: "My Project", route: "/projects" },
      { icon: "person", text: "Team", route: "/team" },
    ],
  }),
};
</script>