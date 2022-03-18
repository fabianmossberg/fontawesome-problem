<script>
import { library, icon } from '@fortawesome/fontawesome-svg-core'
import { faCamera } from '@fortawesome/free-solid-svg-icons'

library.add(faCamera)

const camera = icon({ prefix: 'fas', iconName: 'camera' })
</script>

{@html camera.html}