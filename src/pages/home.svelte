<Page name="home" id="home">
  <!-- Top Navbar -->
  <Navbar>
    <Block class="nav_title">MonItaly</Block>
    <NavRight>
      <Block class="utente"><strong>Utente:</strong></Block>
      <Block id="name_user"><Menu><MenuItem class="opt" text="Accedi" panelOpen="left"/></Menu></Block>
    </NavRight>
  </Navbar>

  <br>
  <Menu>
    <MenuItem class="opt" href="#" text="menu" panelOpen="left"/>
    <MenuItem class="opt" href="/pro/" text="Cerca Prodotti" iconMaterial="bubble_chart"/>
  </Menu>

  <!-- Toolbar -->
  <!--
  <Toolbar bottom>
  <Link href="ciao.txt">Left Link</Link>
  <Link>Accedi</Link>
  </Toolbar>
  -->
  
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