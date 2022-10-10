<Page name="home">
    <!-- Top Navbar -->
    <Navbar >
      <NavTitle class="nav_title2">MonItaly</NavTitle>
      <NavLeft><Link back>Back</Link></NavLeft>
    </Navbar>
  
    <Button class="but" fill on:click={testPrompt}>
      nome e cognome
    </Button>
  
    <!-- Toolbar -->
    <!--
    <Toolbar bottom>
    <Link href="ciao.txt">Left Link</Link>
    <Link>Accedi</Link>
    </Toolbar>
    -->
    
  </Page>
  
  <script>
    const testAlert = () => alert("alert.");
      const testPrompt = async () => {
      let nome = await prompt("Scrivi il tuo nome: ");
      let cognome = await prompt("Scrivi il tuo cognome: ");
      if(nome && cognome){
        //alert(answer);
        document.getElementById('name_user').innerHTML = nome+" - "+cognome;
      }else{
        alert("Compila tutti e due i campi");
      }
    };
    
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