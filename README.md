# taxonomy-image

Create  a js directory inside the taxonomy-image folder than upload this term-image.js there.

# Add your term name (term-image.php)
private $taxonomies = array( 'tour_cat' );

#call Term image

$term = get_term( $term_id ); <br>
wp_get_attachment_image( $term->term_image, 'thumbnail', false, array( 'style' => 'max-width:100%; height:auto;' ) );
