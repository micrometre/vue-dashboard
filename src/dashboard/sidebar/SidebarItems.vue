<script setup lang="ts">
import DocIcon from "./icons/DocIcon.vue";
import SidebarItem from "./SidebarItem.vue";
import TasksIcon from "./icons/TaskIcon.vue";
import ReportsIcon from "./icons/ReportIcon.vue";
import ProjectsIcon from "./icons/ProjectIcon.vue";
import SettingsIcon from "./icons/SettingsIcon.vue";
import CalendarIcon from "./icons/CalendarIcon.vue";
import DashboardIcon from "./icons/DashboardIcon.vue";
import TimeManageIcon from "./icons/TimeManageIcon.vue";
</script>

<template>
  <ul>
    <SidebarItem title="Dashboard" to="/">
      <DashboardIcon />
    </SidebarItem>


    <SidebarItem title="Time Manage" to="/admin/time-manage">
      <TimeManageIcon />
    </SidebarItem>

    <SidebarItem title="Settings" to="/admin/settings">
      <SettingsIcon />
    </SidebarItem>
  </ul>
</template>
