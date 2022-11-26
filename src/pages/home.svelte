<Page name="home" id="home">
  <!-- Top Navbar -->
  <Navbar>
    <Block class="nav_title">SkyBar</Block>
    <NavRight>
      <Menu>
        <MenuItem class="opt" href="#" text="menu" panelOpen="right"/>
      </Menu><br>
    </NavRight>
  </Navbar>

  <br>
</Page>

<script>
  
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Icon,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    theme, 
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';


  export let f7route, f7router; // just to remove debug message
</script>