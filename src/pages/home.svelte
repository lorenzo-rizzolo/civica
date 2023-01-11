<Page name="home" id="home">
  <!-- Top Navbar -->
  <Navbar>
    <Block class="nav_title">Educazione Civica</Block>
    <NavRight>
      <!-- <Button href="#" text="Progetti" panelOpen="right"/> -->
      Lorenzo Rizzolo
    </NavRight>
  </Navbar>

  <center><img src="svelte-welcome.png" alt="welcome"></center>
  <center><h1 class="pres">Benvenuti nel sito di Lorenzo Rizzolo su Educazione Civica.</h1></center>

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