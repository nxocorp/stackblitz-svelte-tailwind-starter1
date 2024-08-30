<script>
    import "../app.css";
    import * as Card from "$lib/components/ui/card";

    let message = "Welcome";

</script>

<Card.Root>
<Card.Header>
  <Card.Title class="text-3xl font-bold underline" >{message} Title</Card.Title>
  <Card.Description>Card Description</Card.Description>
</Card.Header>
<Card.Content>
  <p>Card Content</p>
</Card.Content>
<Card.Footer>
  <p>Card Footer</p>
</Card.Footer>
</Card.Root>



   
